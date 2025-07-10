---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/ftvhelp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FTVHelp` Class Reference

<p>A class that generates a dynamic tree view side panel. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class FTVHelp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/ftvhelp-h">src/ftvhelp.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7d72cccba33233dd89c6280b9ca101">FTVHelp</a> (bool LTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb475096471a3b51feb4b247a41e27c">~FTVHelp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a791c63d8c0dc72e7fedc4f17163dbfa3">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595c544e98100ca8aa84aaea4ac28e9f">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86381415dd788cb4a1a0feac8d5316d8">incContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5949816300bc9d6a104dfd8305aa4e6f">decContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8840ba8f98a6049dbe14bf1c9a236b54">addContentsItem</a> (bool isDir, const QCString &amp;name, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool separateIndex, bool addToNavIndex, const Definition *def, const QCString &amp;nameAsHtml=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b8c0def85d71cd40b3e7ff4596d21f">addIndexItem</a> (const Definition *, const MemberDef *, const QCString &amp;, const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21042205c3db81a63d73a86c2b89f519">addIndexFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2552f43ca499df11f1de1354180dea35">addImageFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac77d9a496836412cbc00d782f404e5">addStyleSheetFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe4b6eab80d4602256ee5edd59b78df">generateTreeView</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7bb7e1b82f56734790565a78e4ef881">generateTreeViewInline</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2b0bf5b5d217f8e0b77b486fed3527">generateTreeViewScripts</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/ftvhelp/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a></td>
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

<p>A class that generates a dynamic tree view side panel.</p>

<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FTVHelp() {#a7e7d72cccba33233dd89c6280b9ca101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FTVHelp::FTVHelp (bool TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Constructs an ftv help object. The object has to be <a href="#a791c63d8c0dc72e7fedc4f17163dbfa3">initialized</a> before it can be used.</p>


<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e7d72cccba33233dd89c6280b9ca101">120</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7e7d72cccba33233dd89c6280b9ca101">FTVHelp::FTVHelp</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> TLI) : <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/ftvhelp/private">Private</a>&gt;(TLI)) {}</span></span></div>

</div>


<p>Reference <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>.</p>


<p>Referenced by <a href="#aacb475096471a3b51feb4b247a41e27c">~FTVHelp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FTVHelp() {#aacb475096471a3b51feb4b247a41e27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FTVHelp::~FTVHelp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<p>Reference <a href="#a7e7d72cccba33233dd89c6280b9ca101">FTVHelp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContentsItem() {#a8840ba8f98a6049dbe14bf1c9a236b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::addContentsItem (bool isDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool separateIndex, bool addToNavIndex, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; nameAsHtml=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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




<p>Add a list item to the contents file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">isDir</td>
<td class="doxyParamItemDescription"><p>TRUE if the item is a directory, FALSE if it is a text</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">name</td>
<td class="doxyParamItemDescription"><p>the name of the item.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">nameAsHtml</td>
<td class="doxyParamItemDescription"><p>the name of the item in HTML format.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ref</td>
<td class="doxyParamItemDescription"><p>the URL of to the item.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">file</td>
<td class="doxyParamItemDescription"><p>the file containing the definition of the item</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">anchor</td>
<td class="doxyParamItemDescription"><p>the anchor within the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">separateIndex</td>
<td class="doxyParamItemDescription"><p>put the entries in a separate index file</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">addToNavIndex</td>
<td class="doxyParamItemDescription"><p>add this entry to the quick navigation index</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">def</td>
<td class="doxyParamItemDescription"><p><a href="/web-doxygen/docs/api/classes/definition">Definition</a> corresponding to this entry</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8840ba8f98a6049dbe14bf1c9a236b54">186</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8840ba8f98a6049dbe14bf1c9a236b54">FTVHelp::addContentsItem</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> separateIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> addToNavIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;nameAsHtml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">                              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p: p-&gt;indent=%d addContentsItem(%d,%s,%s,%s,%s)\n",(void*)this,p-&gt;indent,isDir,qPrint(name),qPrint(ref),qPrint(file),qPrint(anchor));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nl = <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nl.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">    nl.back()-&gt;isLast=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> newNode = std::make_shared&lt;FTVNode&gt;(isDir,ref,file,anchor,name,separateIndex,addToNavIndex,def,nameAsHtml);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  nl.push_back(newNode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  newNode-&gt;index = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(nl.size()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pnl = <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent-1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pnl.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      newNode-&gt;parent = pnl.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aacf6d04a8d8013c15ecc64baa71b6a2f">writeConceptList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a69569b37426082d5d3ce0b547763e64f">writeConceptRootList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>.</p>

</div>
</div>

### addImageFile() {#a2552f43ca499df11f1de1354180dea35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::addImageFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2552f43ca499df11f1de1354180dea35">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2552f43ca499df11f1de1354180dea35">addImageFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### addIndexFile() {#a21042205c3db81a63d73a86c2b89f519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::addIndexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21042205c3db81a63d73a86c2b89f519">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a21042205c3db81a63d73a86c2b89f519">addIndexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### addIndexItem() {#a76b8c0def85d71cd40b3e7ff4596d21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::addIndexItem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76b8c0def85d71cd40b3e7ff4596d21f">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a76b8c0def85d71cd40b3e7ff4596d21f">addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### addStyleSheetFile() {#aeac77d9a496836412cbc00d782f404e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::addStyleSheetFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeac77d9a496836412cbc00d782f404e5">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeac77d9a496836412cbc00d782f404e5">addStyleSheetFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;) {}</span></span></div>

</div>

</div>
</div>

### decContentsDepth() {#a5949816300bc9d6a104dfd8305aa4e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::decContentsDepth ()</td>
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




<p>Decrease the level of the contents hierarchy. This will end the current sublist.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a86381415dd788cb4a1a0feac8d5316d8">incContentsDepth()</a></p></dd>
</dl>


<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5949816300bc9d6a104dfd8305aa4e6f">154</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5949816300bc9d6a104dfd8305aa4e6f">FTVHelp::decContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p: decContentsDepth() indent=%d\n",this,p-&gt;indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nl = <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nl.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a> = nl.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;children = <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent+1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>-&gt;children.push_back(child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      children.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a> and <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>.</p>

</div>
</div>

### finalize() {#a595c544e98100ca8aa84aaea4ac28e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::finalize ()</td>
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




<p>Finalizes the FTV help. This will finish and close the contents file (index.js).</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a791c63d8c0dc72e7fedc4f17163dbfa3">initialize()</a></p></dd>
</dl>


<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a595c544e98100ca8aa84aaea4ac28e9f">134</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a595c544e98100ca8aa84aaea4ac28e9f">FTVHelp::finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0fe4b6eab80d4602256ee5edd59b78df">generateTreeView</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a0fe4b6eab80d4602256ee5edd59b78df">generateTreeView</a>.</p>

</div>
</div>

### generateTreeView() {#a0fe4b6eab80d4602256ee5edd59b78df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::generateTreeView ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 934 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fe4b6eab80d4602256ee5edd59b78df">934</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0fe4b6eab80d4602256ee5edd59b78df">FTVHelp::generateTreeView</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad2b0bf5b5d217f8e0b77b486fed3527">generateTreeViewScripts</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aad2b0bf5b5d217f8e0b77b486fed3527">generateTreeViewScripts</a>.</p>


<p>Referenced by <a href="#a595c544e98100ca8aa84aaea4ac28e9f">finalize</a>.</p>

</div>
</div>

### generateTreeViewInline() {#ac7bb7e1b82f56734790565a78e4ef881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::generateTreeViewInline (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 873 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7bb7e1b82f56734790565a78e4ef881">873</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac7bb7e1b82f56734790565a78e4ef881">FTVHelp::generateTreeViewInline</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> preferredNumEntries = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(HTML_INDEX_NUM_ENTRIES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"directory\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> d=1, depth=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;n : <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[0])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!n-&gt;children.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      d = n-&gt;computeTreeDepth(2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d&gt;depth) depth=d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> preferredDepth = depth;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write level selector</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (depth&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"levels\"&gt;["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDetailLevel();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=1;i&lt;=depth;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span onclick=\"javascript:dynsection.toggleLevel("</span><span class="doxyHighlight"> &lt;&lt; i &lt;&lt; </span><span class="doxyHighlightStringLiteral">");\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; i &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (preferredNumEntries&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">      preferredDepth=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=1;i&lt;=depth;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;n : <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[0])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">          num+=n-&gt;numNodesAtLevel(0,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (num&lt;=preferredNumEntries)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">          preferredDepth=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("preferred depth=%d\n",preferredDepth);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[0].empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"directory\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;generateTree(t,<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[0],0,preferredDepth,index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- directory --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>, <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.</p>

</div>
</div>

### generateTreeViewScripts() {#aad2b0bf5b5d217f8e0b77b486fed3527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::generateTreeViewScripts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 864 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad2b0bf5b5d217f8e0b77b486fed3527">864</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aad2b0bf5b5d217f8e0b77b486fed3527">FTVHelp::generateTreeViewScripts</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> htmlOutput = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// generate navtree.js &amp; navtreeindex.js</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>(<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a> and <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>.</p>


<p>Referenced by <a href="#a0fe4b6eab80d4602256ee5edd59b78df">generateTreeView</a>.</p>

</div>
</div>

### incContentsDepth() {#a86381415dd788cb4a1a0feac8d5316d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::incContentsDepth ()</td>
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




<p>Increase the level of the contents hierarchy. This will start a new sublist in contents file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a5949816300bc9d6a104dfd8305aa4e6f">decContentsDepth()</a></p></dd>
</dl>


<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a86381415dd788cb4a1a0feac8d5316d8">143</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a86381415dd788cb4a1a0feac8d5316d8">FTVHelp::incContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p: incContentsDepth() indent=%d\n",this,p-&gt;indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indentNodes.resize(<a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>-&gt;indent+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>.</p>

</div>
</div>

### initialize() {#a791c63d8c0dc72e7fedc4f17163dbfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FTVHelp::initialize ()</td>
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




<p>This will create a folder tree view table of contents file (tree.js).</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a595c544e98100ca8aa84aaea4ac28e9f">finalize()</a></p></dd>
</dl>


<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>, definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a791c63d8c0dc72e7fedc4f17163dbfa3">126</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a791c63d8c0dc72e7fedc4f17163dbfa3">FTVHelp::initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a0f7e9c1135f7c3aaceef6f3371aaecbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; FTVHelp::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a0f7e9c1135f7c3aaceef6f3371aaecbb">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8840ba8f98a6049dbe14bf1c9a236b54">addContentsItem</a>, <a href="#a5949816300bc9d6a104dfd8305aa4e6f">decContentsDepth</a>, <a href="#a7e7d72cccba33233dd89c6280b9ca101">FTVHelp</a>, <a href="#ac7bb7e1b82f56734790565a78e4ef881">generateTreeViewInline</a>, <a href="#aad2b0bf5b5d217f8e0b77b486fed3527">generateTreeViewScripts</a> and <a href="#a86381415dd788cb4a1a0feac8d5316d8">incContentsDepth</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp">ftvhelp.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
