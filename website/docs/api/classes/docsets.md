---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docsets
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocSets` Class Reference

<p>A class that generates docset files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocSets { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docsets-h">src/docsets.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for index generators. <a href="/web-doxygen/docs/api/classes/indexintf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad050cee55a579c4d01655f2041b5678b">DocSets</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa825df57a02ee969cb4ff64890aeb94f">~DocSets</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cad610aa745779c12a50c3dcf2cdf61">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c00f9b45e88f7907db6a0e7488a7a0b">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5840cce402cd857d80a49275c70d0000">incContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27dd321d6203de4d44b1b3b2fbc0a3a5">decContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fae83e2222326bc3e70dc7f3ada05d5">addContentsItem</a> (bool isDir, const QCString &amp;name, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool separateIndex, bool addToNavIndex, const Definition *def, const QCString &amp;nameAsHtml)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e99525be1bdf8596ca067a014e9931">addIndexItem</a> (const Definition *context, const MemberDef *md, const QCString &amp;sectionAnchor, const QCString &amp;title)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45d63536c188cb4ef6f6f67c5ff4d95">addIndexFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49458eff1e9101d5e5b7e4ab650ce4d">addImageFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9f6c353e1320efebb991a394fae09f">addStyleSheetFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">writeToken</a> (TextStream &amp;t, const Definition *d, const QCString &amp;type, const QCString &amp;lang, const QCString &amp;scope=QCString(), const QCString &amp;anchor=QCString(), const QCString &amp;decl=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/docsets/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d287f46b4a116448f76a6c79785602">p</a></td>
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

<p>A class that generates docset files.</p>


<p>These files can be used to create context help for use within Apple's Xcode 3.0 development environment</p>


<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocSets() {#ad050cee55a579c4d01655f2041b5678b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocSets::DocSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad050cee55a579c4d01655f2041b5678b">44</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad050cee55a579c4d01655f2041b5678b">DocSets::DocSets</a>() : <a href="#a78d287f46b4a116448f76a6c79785602">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/docsets/private">Private</a>&gt;()) {}</span></span></div>

</div>


<p>Reference <a href="#a78d287f46b4a116448f76a6c79785602">p</a>.</p>


<p>Referenced by <a href="#aa825df57a02ee969cb4ff64890aeb94f">~DocSets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DocSets() {#aa825df57a02ee969cb4ff64890aeb94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocSets::~DocSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>.</p>


<p>Reference <a href="#ad050cee55a579c4d01655f2041b5678b">DocSets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContentsItem() {#a2fae83e2222326bc3e70dc7f3ada05d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::addContentsItem (bool isDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool separateIndex, bool addToNavIndex, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; nameAsHtml)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fae83e2222326bc3e70dc7f3ada05d5">225</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2fae83e2222326bc3e70dc7f3ada05d5">DocSets::addContentsItem</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* separateIndex */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* addToNavIndex */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * </span><span class="doxyHighlightComment">/*def*/</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/* nameAsHtml */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  (void)isDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocSets::addContentsItem(%s) depth=%zu\n",name,p-&gt;indentStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.top())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;/Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.top()=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;Name&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(name) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Name&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; file[0]==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// URL marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;URL&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(&amp;file[1])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">            &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/URL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// relative file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;Path&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; file[0]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// user specified file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(&amp;file[1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// doxygen generated file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Path&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;Anchor&gt;"</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Anchor&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a78d287f46b4a116448f76a6c79785602">p</a>.</p>

</div>
</div>

### addImageFile() {#ad49458eff1e9101d5e5b7e4ab650ce4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::addImageFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad49458eff1e9101d5e5b7e4ab650ce4d">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad49458eff1e9101d5e5b7e4ab650ce4d">addImageFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### addIndexFile() {#ad45d63536c188cb4ef6f6f67c5ff4d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::addIndexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 511 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad45d63536c188cb4ef6f6f67c5ff4d95">511</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad45d63536c188cb4ef6f6f67c5ff4d95">DocSets::addIndexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">  (void)name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### addIndexItem() {#a68e99525be1bdf8596ca067a014e9931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::addIndexItem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * context, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectionAnchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68e99525be1bdf8596ca067a014e9931">273</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *context,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; context==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd      = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd     = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">    fd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    cd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    nd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// internal symbol</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> decl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// determine language</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = SrcLangExt::Cpp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    langExt = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    langExt = context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Cpp:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::ObjC:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md &amp;&amp; (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aae943a44f4314a00a9572d0fa5e364e7">isObjCProperty</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">          lang=</span><span class="doxyHighlightStringLiteral">"occ"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightComment">// Objective C/C++</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd &amp;&amp; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".c"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">          lang=</span><span class="doxyHighlightStringLiteral">"c"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightComment">// Plain C</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; nd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">          lang=</span><span class="doxyHighlightStringLiteral">"c"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightComment">// Plain C symbol outside any class or namespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">          lang=</span><span class="doxyHighlightStringLiteral">"cpp"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightComment">// C++</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::IDL:     lang=</span><span class="doxyHighlightStringLiteral">"idl"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;        </span><span class="doxyHighlightComment">// IDL</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::CSharp:  lang=</span><span class="doxyHighlightStringLiteral">"csharp"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;     </span><span class="doxyHighlightComment">// C#</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::PHP:     lang=</span><span class="doxyHighlightStringLiteral">"php"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;        </span><span class="doxyHighlightComment">// PHP4/5</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::D:       lang=</span><span class="doxyHighlightStringLiteral">"d"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;          </span><span class="doxyHighlightComment">// D</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Java:    lang=</span><span class="doxyHighlightStringLiteral">"java"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;       </span><span class="doxyHighlightComment">// Java</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::JS:      lang=</span><span class="doxyHighlightStringLiteral">"javascript"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// JavaScript</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Python:  lang=</span><span class="doxyHighlightStringLiteral">"python"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;     </span><span class="doxyHighlightComment">// Python</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Fortran: lang=</span><span class="doxyHighlightStringLiteral">"fortran"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;    </span><span class="doxyHighlightComment">// Fortran</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::VHDL:    lang=</span><span class="doxyHighlightStringLiteral">"vhdl"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;       </span><span class="doxyHighlightComment">// VHDL</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::XML:     lang=</span><span class="doxyHighlightStringLiteral">"xml"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;        </span><span class="doxyHighlightComment">// DBUS XML</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::SQL:     lang=</span><span class="doxyHighlightStringLiteral">"sql"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;        </span><span class="doxyHighlightComment">// Sql</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Markdown:lang=</span><span class="doxyHighlightStringLiteral">"markdown"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">// Markdown</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Slice:   lang=</span><span class="doxyHighlightStringLiteral">"slice"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;      </span><span class="doxyHighlightComment">// Slice</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Lex:     lang=</span><span class="doxyHighlightStringLiteral">"lex"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;        </span><span class="doxyHighlightComment">// Lex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> SrcLangExt::Unknown: lang=</span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;    </span><span class="doxyHighlightComment">// should not happen!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context &amp;&amp; md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"macro"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">MemberType::Function</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd &amp;&amp; (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">              cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">            type=</span><span class="doxyHighlightStringLiteral">"clm"</span><span class="doxyHighlight">;         </span><span class="doxyHighlightComment">// class member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">            type=</span><span class="doxyHighlightStringLiteral">"instm"</span><span class="doxyHighlight">;       </span><span class="doxyHighlightComment">// instance member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd &amp;&amp; cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">            type=</span><span class="doxyHighlightStringLiteral">"intfcm"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightComment">// interface class member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">            type=</span><span class="doxyHighlightStringLiteral">"intfm"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightComment">// interface member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">          type=</span><span class="doxyHighlightStringLiteral">"func"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"data"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">MemberType::Typedef</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"tdef"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"econst"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//case MemberDef::Prototype:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//  type="prototype"; break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">MemberType::Signal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">MemberType::Slot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"slot"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">MemberType::Friend</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"ffunc"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">MemberType::DCOP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"dcop"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">MemberType::Property</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd &amp;&amp; cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">          type=</span><span class="doxyHighlightStringLiteral">"intfp"</span><span class="doxyHighlight">;         </span><span class="doxyHighlightComment">// interface property</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">          type=</span><span class="doxyHighlightStringLiteral">"instp"</span><span class="doxyHighlight">;         </span><span class="doxyHighlightComment">// instance property</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">MemberType::Event</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"event"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">MemberType::Interface</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"ifc"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">MemberType::Service</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"svc"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">MemberType::Sequence</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">MemberType::Dictionary</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"dictionary"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">    scope = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    fd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">      decl = fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">writeToken</a>(<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts,md,type,lang,scope,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),decl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context &amp;&amp; context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">      fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">      cd = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">      nd = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">      type=</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">      scope = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">isTemplate</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"tmplt"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"intf"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">)) scope=scope.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"cl"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">ClassDef::Category</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">        type=</span><span class="doxyHighlightStringLiteral">"cat"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">        type = </span><span class="doxyHighlightStringLiteral">"cl"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *ii = cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">includeInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">        decl=ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      scope = nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      type = </span><span class="doxyHighlightStringLiteral">"ns"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;scopes.find(context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;scopes.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">writeToken</a>(<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts,context,type,lang,scope,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),decl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;scopes.insert(context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">ClassDef::Category</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">ClassDef::compoundType</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">DCOP</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">Define</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">Dictionary</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">Enumeration</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">Event</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">Friend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">Function</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">MemberDef::getNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a68246f42d892a0cd4e1b5248d8f8f947">MemberDef::getScopeString</a>, <a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">ClassDef::includeInfo</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">IncludeInfo::includeName</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">Interface</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">MemberDef::isObjCMethod</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aae943a44f4314a00a9572d0fa5e364e7">MemberDef::isObjCProperty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">MemberDef::isStatic</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">ClassDef::isTemplate</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a78d287f46b4a116448f76a6c79785602">p</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">Property</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">Sequence</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">Service</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">Signal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">Slot</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a> and <a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">writeToken</a>.</p>

</div>
</div>

### addStyleSheetFile() {#aea9f6c353e1320efebb991a394fae09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::addStyleSheetFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea9f6c353e1320efebb991a394fae09f">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea9f6c353e1320efebb991a394fae09f">addStyleSheetFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### decContentsDepth() {#a27dd321d6203de4d44b1b3b2fbc0a3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::decContentsDepth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27dd321d6203de4d44b1b3b2fbc0a3a5">214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27dd321d6203de4d44b1b3b2fbc0a3a5">DocSets::decContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.top())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;/Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Subnodes&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocSets::decContentsDepth() depth=%zu\n",p-&gt;indentStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a78d287f46b4a116448f76a6c79785602">p</a>.</p>

</div>
</div>

### finalize() {#a8c00f9b45e88f7907db6a0e7488a7a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::finalize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 181 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c00f9b45e88f7907db6a0e7488a7a0b">181</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c00f9b45e88f7907db6a0e7488a7a0b">DocSets::finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.top())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;/Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/Subnodes&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/TOC&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/DocSetNodes&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts.flush();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ntf.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Tokens&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts.flush();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ttf.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a78d287f46b4a116448f76a6c79785602">p</a>.</p>

</div>
</div>

### incContentsDepth() {#a5840cce402cd857d80a49275c70d0000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::incContentsDepth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5840cce402cd857d80a49275c70d0000">207</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5840cce402cd857d80a49275c70d0000">DocSets::incContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocSets::incContentsDepth() depth=%zu\n",p-&gt;indentStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indent() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;Subnodes&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.push(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a78d287f46b4a116448f76a6c79785602">p</a>.</p>

</div>
</div>

### initialize() {#a7cad610aa745779c12a50c3dcf2cdf61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::initialize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cad610aa745779c12a50c3dcf2cdf61">47</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7cad610aa745779c12a50c3dcf2cdf61">DocSets::initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// -- get config options</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (projectName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) projectName=</span><span class="doxyHighlightStringLiteral">"root"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bundleId = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCSET_BUNDLE_ID);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bundleId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) bundleId=</span><span class="doxyHighlightStringLiteral">"org.doxygen.Project"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> feedName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCSET_FEEDNAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (feedName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) feedName=</span><span class="doxyHighlightStringLiteral">"FeedName"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> feedURL = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCSET_FEEDURL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (feedURL.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) feedURL=</span><span class="doxyHighlightStringLiteral">"FeedUrl"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> publisherId = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCSET_PUBLISHER_ID);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (publisherId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) publisherId=</span><span class="doxyHighlightStringLiteral">"PublisherId"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> publisherName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCSET_PUBLISHER_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (publisherName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) publisherName=</span><span class="doxyHighlightStringLiteral">"PublisherName"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectNumber = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NUMBER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (projectNumber.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) projectNumber=</span><span class="doxyHighlightStringLiteral">"ProjectNumber"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// -- write Makefile</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mfName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/Makefile"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream ts = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(mfName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ts.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,mfName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    ts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOCSET_NAME="</span><span class="doxyHighlight"> &lt;&lt; bundleId &lt;&lt; </span><span class="doxyHighlightStringLiteral">".docset\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"DOCSET_CONTENTS=$(DOCSET_NAME)/Contents\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"DOCSET_RESOURCES=$(DOCSET_CONTENTS)/Resources\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"DOCSET_DOCUMENTS=$(DOCSET_RESOURCES)/Documents\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"DESTDIR=~/Library/Developer/Shared/Documentation/DocSets\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"XCODE_INSTALL=\"$(shell xcode-select -print-path)\"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"all: docset\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"docset:\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tmkdir -p $(DOCSET_DOCUMENTS)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tcp Nodes.xml $(DOCSET_RESOURCES)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tcp Tokens.xml $(DOCSET_RESOURCES)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tcp Info.plist $(DOCSET_CONTENTS)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\ttar --exclude $(DOCSET_NAME) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t    --exclude Nodes.xml \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t    --exclude Tokens.xml \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t    --exclude Info.plist \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t    --exclude Makefile -c -f - . \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t    | (cd $(DOCSET_DOCUMENTS); tar xvf -)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\t$(XCODE_INSTALL)/usr/bin/docsetutil index $(DOCSET_NAME)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -f $(DOCSET_DOCUMENTS)/Nodes.xml\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -f $(DOCSET_DOCUMENTS)/Info.plist\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -f $(DOCSET_DOCUMENTS)/Makefile\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -f $(DOCSET_RESOURCES)/Nodes.xml\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -f $(DOCSET_RESOURCES)/Tokens.xml\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"clean:\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -rf $(DOCSET_NAME)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"install: docset\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tmkdir -p $(DESTDIR)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\tcp -R $(DOCSET_NAME) $(DESTDIR)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"uninstall:\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\trm -rf $(DESTDIR)/$(DOCSET_NAME)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"always:\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// -- write Info.plist</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> plName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/Info.plist"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream ts = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(plName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ts.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,plName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    ts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version=\"1.0\" encoding=\"UTF-8\"?&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"&lt;!DOCTYPE plist PUBLIC \"-//Apple Computer//DTD PLIST 1.0//EN\"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\"http://www.apple.com/DTDs/PropertyList-1.0.dtd\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"&lt;plist version=\"1.0\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"&lt;dict&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;CFBundleName&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; projectName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;CFBundleIdentifier&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; bundleId &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;CFBundleVersion&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; projectNumber &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DocSetFeedName&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; feedName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DocSetFeedUrl&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; feedURL &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DocSetPublisherIdentifier&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; publisherId &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DocSetPublisherName&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;"</span><span class="doxyHighlight"> &lt;&lt; publisherName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// markers for Dash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DashDocSetFamily&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;doxy&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;key&gt;DocSetPlatformFamily&lt;/key&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"     &lt;string&gt;doxygen&lt;/string&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"&lt;/dict&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"&lt;/plist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// -- start Nodes.xml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> notes = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/Nodes.xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ntf = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(notes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ntf.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,notes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts.setStream(&amp;<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ntf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//QCString indexName=Config_getBool(GENERATE_TREEVIEW)?"main":"index";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> indexName=</span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version=\"1.0\" encoding=\"UTF-8\"?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;DocSetNodes version=\"1.0\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;TOC&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;Node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Name&gt;Root&lt;/Name&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Path&gt;"</span><span class="doxyHighlight"> &lt;&lt; indexName &lt;&lt; <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Path&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;nts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Subnodes&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;indentStack.push(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tokens = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/Tokens.xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ttf = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(tokens);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ttf.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,tokens);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts.setStream(&amp;<a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;ttf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version=\"1.0\" encoding=\"UTF-8\"?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a78d287f46b4a116448f76a6c79785602">p</a>-&gt;tts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;Tokens version=\"1.0\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#a78d287f46b4a116448f76a6c79785602">p</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### writeToken() {#a0c852a5df0dd82d83c4ec8b99f4e3937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSets::writeToken (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lang, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scope=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; decl=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>, definition at line 466 of file <a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">466</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c852a5df0dd82d83c4ec8b99f4e3937">DocSets::writeToken</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lang,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;decl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;Token&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;TokenIdentifier&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">))  name=name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Name&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(name) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Name&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lang.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;APILanguage&gt;"</span><span class="doxyHighlight"> &lt;&lt; lang &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/APILanguage&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!type.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Type&gt;"</span><span class="doxyHighlight"> &lt;&lt; type &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Type&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;Scope&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(scope) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Scope&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/TokenIdentifier&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;Path&gt;"</span><span class="doxyHighlight"> &lt;&lt; fn &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Path&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;Anchor&gt;"</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Anchor&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tooltip.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;Abstract&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(tooltip) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/Abstract&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!decl.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;DeclaredIn&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(decl) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/DeclaredIn&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/Token&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="#a68e99525be1bdf8596ca067a014e9931">addIndexItem</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a78d287f46b4a116448f76a6c79785602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; DocSets::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78d287f46b4a116448f76a6c79785602">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a78d287f46b4a116448f76a6c79785602">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a2fae83e2222326bc3e70dc7f3ada05d5">addContentsItem</a>, <a href="#a68e99525be1bdf8596ca067a014e9931">addIndexItem</a>, <a href="#a27dd321d6203de4d44b1b3b2fbc0a3a5">decContentsDepth</a>, <a href="#ad050cee55a579c4d01655f2041b5678b">DocSets</a>, <a href="#a8c00f9b45e88f7907db6a0e7488a7a0b">finalize</a>, <a href="#a5840cce402cd857d80a49275c70d0000">incContentsDepth</a> and <a href="#a7cad610aa745779c12a50c3dcf2cdf61">initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docsets-cpp">docsets.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docsets-h">docsets.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
