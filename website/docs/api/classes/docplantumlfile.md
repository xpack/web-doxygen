---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docplantumlfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocPlantUmlFile` Class Reference

<p>Node representing a uml file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocPlantUmlFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docdiagramfilebase">DocDiagramFileBase</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c47df6bcc6c6ce636b6a6898e27bd3">DocPlantUmlFile</a> (DocParser *parser, DocNodeVariant *parent, const QCString &amp;name, const QCString &amp;context, const QCString &amp;srcFile, int srcLine)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced065805a867717cc792ae759c96876">parse</a> ()</td>
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

<p>Node representing a uml file.</p>

<p>Definition at line 739 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocPlantUmlFile() {#a31c47df6bcc6c6ce636b6a6898e27bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocPlantUmlFile::DocPlantUmlFile (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 742 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 1207 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31c47df6bcc6c6ce636b6a6898e27bd3">1207</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a31c47df6bcc6c6ce636b6a6898e27bd3">DocPlantUmlFile::DocPlantUmlFile</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae48977f85ee8fa8bdf1e85bf963913c6">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">context</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ac8c7ca27050ecec9a3c70ebfdcbef386">DocDiagramFileBase</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae48977f85ee8fa8bdf1e85bf963913c6">name</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">context</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;relPath = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>-&gt;context.relPath;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">DocDiagramFileBase::context</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ac8c7ca27050ecec9a3c70ebfdcbef386">DocDiagramFileBase::DocDiagramFileBase</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae48977f85ee8fa8bdf1e85bf963913c6">DocDiagramFileBase::name</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">DocDiagramFileBase::p</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#aced065805a867717cc792ae759c96876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocPlantUmlFile::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 744 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 1214 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aced065805a867717cc792ae759c96876">1214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aced065805a867717cc792ae759c96876">DocPlantUmlFile::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>(<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8e0ea841cb1abdf12857f32524b5f8d3">CommandType::CMD_PLANTUMLFILE</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;width,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a164ac0911619d2207f585971a08c73c7">Doxygen::plantUmlFileNameLinkedMap</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name.endsWith(</span><span class="doxyHighlightStringLiteral">".puml"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// try with .puml extension as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">    fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a164ac0911619d2207f585971a08c73c7">Doxygen::plantUmlFileNameLinkedMap</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name+</span><span class="doxyHighlightStringLiteral">".puml"</span><span class="doxyHighlight">,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name.endsWith(</span><span class="doxyHighlightStringLiteral">".pu"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// try with .pu extension as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">      fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a164ac0911619d2207f585971a08c73c7">Doxygen::plantUmlFileNameLinkedMap</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name+</span><span class="doxyHighlightStringLiteral">".pu"</span><span class="doxyHighlight">,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;file = fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">    ok = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ambig)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">context</a>.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"included uml file name '{}' is ambiguous.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"Possible candidates:\n{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a164ac0911619d2207f585971a08c73c7">Doxygen::plantUmlFileNameLinkedMap</a>,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">context</a>.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"included uml file '{}' is not found "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"in any of the paths specified via PLANTUMLFILE_DIRS!"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">p</a>-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8e0ea841cb1abdf12857f32524b5f8d3">CMD_PLANTUMLFILE</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae2d576fe18bfd94d99f8fb94aec969bf">DocDiagramFileBase::context</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a8ce036068cb5eae464960a34ba3152af">DocDiagramFileBase::p</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a164ac0911619d2207f585971a08c73c7">Doxygen::plantUmlFileNameLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
