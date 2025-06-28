---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/rtfdocvisitor-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `rtfdocvisitor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;algorithm&gt;
#include "<a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/rtfgen-h">rtfgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dia-h">dia.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c683042be29f8f10d539f4a01a03237">align</a> (const DocHtmlCell &amp;cell)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a> (const QCString &amp;name)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
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

### align() {#a1c683042be29f8f10d539f4a01a03237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString align (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; cell)</td>
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


<p>Definition at line <a href="#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c683042be29f8f10d539f4a01a03237">45</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1c683042be29f8f10d539f4a01a03237">align</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;cell)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;attr : cell.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (attr.name.lower()==</span><span class="doxyHighlightStringLiteral">"align"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (attr.value.lower()==</span><span class="doxyHighlightStringLiteral">"center"</span><span class="doxyHighlight">)     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\\qc "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (attr.value.lower()==</span><span class="doxyHighlightStringLiteral">"right"</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\\qr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">DocHtmlCell::attribs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a70c61ff58fa9f747fc2b971c689a09ff">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#a45d8c190fc894d6743423e628c19294b">OutputGenIntf::startMemberDocName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b9d56f0ab609c25ba0b449e4d977f80">OutputList::startMemberDocName</a>.
</div>
</div>

### makeBaseName() {#a809219d7701732d9db2bbfef99c3e86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeBaseName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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


<p>Definition at line <a href="#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a809219d7701732d9db2bbfef99c3e86b">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName=baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DBG&#95;RTF {#a8e937453cd49cd7e753fa4e9d77d3c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DBG_RTF(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00043">43</a> of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e937453cd49cd7e753fa4e9d77d3c38">43</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DBG_RTF(x) do {} while(0)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9c567713ffb6a4b9a49400d6dfcb0df1">RTFGenerator::addLabel</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3a64ef0ca4a6a8f00c6b38e80e9d4545">RTFGenerator::beginRTFChapter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a511d5ad66a598b2607224d1d1b1a931e">RTFCodeGenerator::endCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae03eee47f94ec96943747c15069e3c5b">RTFGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06931a0616d950c5388448188105c4c1">RTFGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae7bfacd8071ffd9098ea45614589512a">RTFGenerator::endConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a095b00a37d39558c622e5a6845212b1e">RTFGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a41d0580039dd59b0489caa356b4ccad5">RTFGenerator::endDescForItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a184f64bfd9c98146ba14cb7f990b66fd">RTFGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a17f06e3f5f32ffba2bd20391454b832f">RTFGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af4494ff8c7b1bfad186fa98542bb6f41">RTFGenerator::endDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa38cd77d33e0757270082a234e53c22d">RTFGenerator::endDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a69e6795499d9f7fb8867f5496c590e26">RTFGenerator::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afda973c4c7b91577d02465015737763d">RTFGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8f58df9f7518582ab2fc88326d539f1b">RTFGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad4d65d3f43a0ca0ff1e6cc7564a0164c">RTFGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a884c87751b85f4a6cf6e965fbc0bec9c">RTFGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac7cc1ced007f53858bf3f0e45a4db2b2">RTFGenerator::endIndexKey</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac49acd6dde35e8774990922cad8b953f">RTFGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af5e47f880bf9f49092c9bd4da6229803">RTFGenerator::endIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae32c0528c173d54061e225bb9ecac3d4">RTFGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3e7490832bc015173929fd693aa0f74">RTFGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac4f20b0496b985dc382d29d6a93227cd">RTFGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a456b03ed29381d753fa5ca17494b24e1">RTFGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3fe406eec950115eb22d5db49f874028">RTFGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4d8ad4d2dbb3a431808692d286ad4331">RTFGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aac0b61c1ae1d31008316991d86290451">RTFGenerator::endItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a94002731a870c5add8c360dda5f5105d">RTFGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a78507d411bc9c250de2db0d0fe4cd323">RTFGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5936c81e07c1d5c6532d42a7ea881296">RTFGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a52336db808f8c14a307dfe212cb2dccf">RTFGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5520b73ff0e7fd88b3b786a81ff05dbe">RTFGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a01d9e19175b7f2f875be520f1ea105b3">RTFGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a2aa043554c3f70e4525bc68978ce1fae">RTFGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a08d35b8ea8ee7a13d1f0b6cbb57d8b0c">RTFGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6f55850d073b6a3f48452ae91e3ab319">RTFGenerator::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac504083f94cbb2fb24d005200efdd7ee">RTFGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae1d2406e88f94dc7d09bb2f339a2ae14">RTFGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a845289f973bb5776db928e02da765a9b">RTFGenerator::endProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9fd2d69fc49bd907eb78fdd08c8f7f2a">RTFGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a64bae8b15a87dc0384440f8143952b7d">RTFGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac82e6d2bb73a007715d4ccf10552848d">RTFGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a55a01085b53c2fdb7176edfa10ebcc7b">RTFGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4354834197f45954df7a81d84f70c34d">RTFGenerator::lastIndexPage</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc07a6f4ee440625b9fff2890651b092">RTFGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a19bbf6e08804ee457c7aa9e07b833ba0">RTFGenerator::newParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2993bfecac33a60da6408f79586b7da2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a74283afcc3656534bef009b917a9f525">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a39a5bf02292d858e211a2cb3ee3f62c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8991833ac99826e07a993af4b58b0c4b">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a33dd9566336e1d3c40ea2dadff6d8676">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4af0a6415a019a1051dda0dd4d56dbef">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a485c2a5796bb5e12497c7ab9d65d1f8c">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a022f6eb89bc55b752aeff008e9c9037d">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a44f9db74256f38af950876f6863a1dd4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a70c61ff58fa9f747fc2b971c689a09ff">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a85db1985a82081ef9ab2e5a25c450f28">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8d4eb63da29c3a07a95f240dcd9a143e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ae0c5c194fc2579df52204eb00134c6bf">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#acc6c497f52cf55d67723f21ec2a97c6b">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2851bbf082cd6f2a85d6c9fc7a1050c0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a63f63207a160e4e99a4c2dd5b55734c8">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7a5ce880ef222be6eeb6eea7e12b78b8">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3c72fc623be48174c003bb47c523d6c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a247c4506996a3a6d71827322614efb30">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aed6822c7504330f96cc764e333589e7a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3db5842a73ae3417854ddcd60b0e1d12">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a561b27cc775aaa5f6db73f1d33099176">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a9a4d703a5dab4d351818ffdf686dccd1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a23778040c53c76ac927398e0e728ffb5">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a732b1d92dfc620e4cb221bbb32fade22">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af6ff0afe39093628cd96d42dfce7515f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4f3ac1fc0fb8cb8218beb807d0a820d1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa547c49d64497e4774d3405b9cdcf7f1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a07acb7803948c3811f88d4efa00587a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3ccfb63934cef53d78e3e6641be084b5">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4fcb960f7e5b593e8e6c51ea43f66a9a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a9bc7acec72efe2239cb6c798855ed08a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#add264d5a56e09e76ec274af99af747d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8123582499bf0458dc938ff66c4724e7">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a9dc9aeca576eb153d222793bc3227d07">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac06a6ad599b271d16500b483b5912679">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a74f1097897a6deaeffd0ca3ca9e5c811">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af154c4b8688beaef882211c40763fec3">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8a5645c1c20ae4026ceb059b942e2635">RTFGenerator::rtfwriteRuler&#95;doubleline</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9bc01f00c980b0cb98c25c0af7f7cea1">RTFGenerator::rtfwriteRuler&#95;emboss</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a32c6af73c41ff6bb6233031279e6ed5d">RTFGenerator::rtfwriteRuler&#95;thick</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abde344bf39163a6d4d42e4185c545edb">RTFGenerator::rtfwriteRuler&#95;thin</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a05a8c27946c7617a908964ccc7887a30">RTFGenerator::startCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac00a39db660145867a1bc5b82ad1abb8">RTFGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acd2fed43ebf5f693abe84471a520cbe9">RTFCodeGenerator::startCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7db2fcbd4306f608b3218666cffc4752">RTFGenerator::startConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a29a84d512d59f79ef193e7b0f5010a9d">RTFGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af9760387169c66c34e3d3acbb29c03e5">RTFGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac6f532b4c8ab36466d7acdb54d26e55a">RTFGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7eb596117c50d366babde83c40af8920">RTFGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab4f116084ff07d558fd61db56501e61d">RTFGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a17f0ea04371269d3dccee931c410c3ff">RTFGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4e30c4664b1c3cc9a1cb26a2ae98968d">RTFGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8454a525177779c9bb183b0ad36fa56b">RTFGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5e490251eafaf1e6daea2205501855e2">RTFGenerator::startDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5fd513f89fced258355f7b28f13ec886">RTFGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae8d815b1579cfc5304f25b4b3c4bca24">RTFGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad69c3570dc9ede5dd3058791e252c3cc">RTFGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc0d8b219f558b257eed6bb523c79fab">RTFGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac780414967a7bdbad20d2323d8b7098f">RTFGenerator::startInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a434d17937e0e38eb2a631866282cece0">RTFGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9a13eaff7928b82d69f9547aa004d107">RTFGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a28728cc8dec08d2a29432ce9b1ddd443">RTFGenerator::startIndexKey</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a969f88aefb693d90e5ced9f91a20b4bc">RTFGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a2fef63d61742f328f7b3a036d367c53f">RTFGenerator::startIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abebfc200cb6a3b894069dd00fee75649">RTFGenerator::startIndexValue</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aedc9cfff56c51ffc2bae28353a319b2e">RTFGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3f1c345322088ffb63e9075c292ec10">RTFGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a131090d6366f73af154c7e59c40bff03">RTFGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab8777ce4032e78dc5a34d5569c09dcc1">RTFGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa3e5b3dfc4338ba018f1f728d47735f0">RTFGenerator::startItemList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6847cacb71fc0487655971490b6eb778">RTFGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afccb8a5712c326ee5cee2a0caea2bbb1">RTFGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aacbda0698357ec14331ff4ff82f3a2ab">RTFGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abbafc50a4d1a1c021aa659883d40ef45">RTFGenerator::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#acb4071607f13b1efd3de13a9e3e37fdd">RTFGenerator::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7ec7eb8980ebddb6c74f2db073e9ab76">RTFGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa37f27c3476aa545d3e364b3df70baa8">RTFGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af228acba3f28d35809c7e430b850b821">RTFGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5e6c5dd7997b60786df03efbfa3a04f2">RTFGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7e3e11ada289af78620b5c6d9733c9">RTFGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a775d9cad2024f07bb3e760e86e6267d4">RTFGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae99a950db4933f16e3df97021e696318">RTFGenerator::startProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a012cbbfdb3b792d3d0204004cc7d7772">RTFGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa7ae50a52d4e01f107667b89ead7b3a3">RTFGenerator::writeAnchor</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06cb016c789f240eabead87f1a10325a">RTFGenerator::writeStartAnnoItem</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
