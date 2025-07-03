---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outputcodelist
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputCodeList` Class Reference

<p>Class representing a list of different code generators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class OutputCodeList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/outputlist-h">src/outputlist.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ca8e5197d97fe6e8650a1949457ac0">setId</a> (int id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b7d69b02fe400d0111a3321c9f0265">add</a> (OutputCodeIntfPtr &amp;&amp;p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a140918bf6841d5fa572a58a7a59eece9">add</a> (As &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a code generator to the list, using a syntax similar to std::make_unique&lt;T&gt;() <a href="#a140918bf6841d5fa572a58a7a59eece9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3320211f0fe2d7cdcced9f93ccd8ab61">get</a> (OutputType o)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to a specific generator in the list. <a href="#a3320211f0fe2d7cdcced9f93ccd8ab61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa698fb8d956eefe27034d2030751a002">setEnabledFiltered</a> (OutputType o, bool enabled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable or disable a specific generator. <a href="#aa698fb8d956eefe27034d2030751a002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3366931e582bd83073396e0a95ce7c">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346e7da814676d131ff5dc6df4e2726b">codify</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a> (bool b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639977987188046433fd28e1bc9a766c">startSpecialComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1670c0ebaeda05f89224f58230f497">endSpecialComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc8bc3fc3e31c071445debd32a564ed">setStripIndentAmount</a> (size_t amount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb20173014b60bceb6f75a621749f73">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08d11446544b377ebb9a66f76e0a1ad">writeLineNumber</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, int lineNumber, bool writeLineAnchor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f3db752795807f3c67e25f6fdcb081">writeTooltip</a> (const QCString &amp;id, const DocLinkInfo &amp;docInfo, const QCString &amp;decl, const QCString &amp;desc, const SourceLinkInfo &amp;defInfo, const SourceLinkInfo &amp;declInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09941fc041983198d326b3b7cdc4795">startCodeLine</a> (int lineNr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b77a46a240ee024adafb99578ed91b">endCodeLine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f1dacf0a9323f4471c33f81c1319d9">startFontClass</a> (const QCString &amp;c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8bf2af17093b84e10f15400afe9f5c">endFontClass</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759bd4d05586bd782adfd25ce635079f">writeCodeAnchor</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c741566f88d0cdbf6bdfceba362c5d">startCodeFragment</a> (const QCString &amp;style)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd1a41f54ede1bb82197ea2b45cf78e">endCodeFragment</a> (const QCString &amp;style)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8fb201274cdd71281a93021e2d003d4">startFold</a> (int lineNr, const QCString &amp;startMarker, const QCString &amp;endMarker)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f74862395c35b76e6650dcfd942d6c6">endFold</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83e76d5788ad3b3cc9142cbcc67edca6">foreach</a> (void(OutputCodeIntf::*methodPtr)(Ts...), As &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/outputcodelist/outputcodeelem">OutputCodeElem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a> = -1</td>
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

<p>Class representing a list of different code generators.</p>


<p>It offers the same interface as the specific code generators, and will forward each method to all generators that are enabled.</p>


<p>Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OutputCodeIntfPtr {#ad0248da81685b845dbcb3be28f243fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OutputCodeList::OutputCodeIntfPtr =  std::unique_ptr&lt;OutputCodeIntf&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0248da81685b845dbcb3be28f243fe6">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> = std::unique_ptr&lt;OutputCodeIntf&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a60b7d69b02fe400d0111a3321c9f0265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::add (<a href="#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> &amp;&amp; p)</td>
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



<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60b7d69b02fe400d0111a3321c9f0265">194</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a60b7d69b02fe400d0111a3321c9f0265">add</a>(<a href="#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> &amp;&amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.emplace_back(std::move(p));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>


<p>Referenced by <a href="#a140918bf6841d5fa572a58a7a59eece9">add</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a45427ad8a509ed14c5f6c1ef1a64e5d7">DocbookGenerator::addCodeGen</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab7780b856bce0c4e0ea29e92fec08dce">HtmlGenerator::addCodeGen</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a019e5d73adb47b293289531bf8431dd4">LatexGenerator::addCodeGen</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a21756c4404bc9061c6d5691ced263a08">ManGenerator::addCodeGen</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aac388fe5f65f2e3d8acb66b1466b2f0b">RTFGenerator::addCodeGen</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#ae8dd6bba2e9ad92dab454422a3136a26">generateHtmlOutput</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3931b4604b8a76ac26b7380a585ef543">FileDefImpl::parseSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6d391007591f277cd73420b77403666d">writeXMLCodeBlock</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a>.</p>

</div>
</div>

### add() {#a140918bf6841d5fa572a58a7a59eece9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * OutputCodeList::add (As &amp;&amp;... args)</td>
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

<p>Add a code generator to the list, using a syntax similar to std::make_unique&lt;T&gt;()</p>

<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a140918bf6841d5fa572a58a7a59eece9">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a140918bf6841d5fa572a58a7a59eece9">add</a>(As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a60b7d69b02fe400d0111a3321c9f0265">add</a>(std::make_unique&lt;T&gt;(std::forward&lt;As&gt;(args)...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.back().intf.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a60b7d69b02fe400d0111a3321c9f0265">add</a> and <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>

</div>
</div>

### clear() {#a8f3366931e582bd83073396e0a95ce7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::clear ()</td>
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



<p>Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f3366931e582bd83073396e0a95ce7c">227</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8f3366931e582bd83073396e0a95ce7c">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>

</div>
</div>

### codify() {#a346e7da814676d131ff5dc6df4e2726b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a346e7da814676d131ff5dc6df4e2726b">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a346e7da814676d131ff5dc6df4e2726b">codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#ac197cae8111e4ab46a420bb60e7a5cf7">OutputCodeIntf::codify</a>,s); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#ac197cae8111e4ab46a420bb60e7a5cf7">OutputCodeIntf::codify</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>.</p>

</div>
</div>

### endCodeFragment() {#abcd1a41f54ede1bb82197ea2b45cf78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcd1a41f54ede1bb82197ea2b45cf78e">281</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abcd1a41f54ede1bb82197ea2b45cf78e">endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#aaf0512eb0fba99581a71b69af3a34022">OutputCodeIntf::endCodeFragment</a>,style); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#aaf0512eb0fba99581a71b69af3a34022">OutputCodeIntf::endCodeFragment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6d391007591f277cd73420b77403666d">writeXMLCodeBlock</a>.</p>

</div>
</div>

### endCodeLine() {#a27b77a46a240ee024adafb99578ed91b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::endCodeLine ()</td>
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



<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27b77a46a240ee024adafb99578ed91b">266</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27b77a46a240ee024adafb99578ed91b">endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a6105e340a5227e374436891bb8bec7c4">OutputCodeIntf::endCodeLine</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a6105e340a5227e374436891bb8bec7c4">OutputCodeIntf::endCodeLine</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a> and <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>.</p>

</div>
</div>

### endFold() {#a3f74862395c35b76e6650dcfd942d6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::endFold ()</td>
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



<p>Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f74862395c35b76e6650dcfd942d6c6">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3f74862395c35b76e6650dcfd942d6c6">endFold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a127a4783dec15638ad6784e4fe4a4184">OutputCodeIntf::endFold</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a127a4783dec15638ad6784e4fe4a4184">OutputCodeIntf::endFold</a>.</p>

</div>
</div>

### endFontClass() {#a8c8bf2af17093b84e10f15400afe9f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::endFontClass ()</td>
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



<p>Definition at line 272 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c8bf2af17093b84e10f15400afe9f5c">272</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c8bf2af17093b84e10f15400afe9f5c">endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#aa45791b7a34c31f98cfa5b415feda4b7">OutputCodeIntf::endFontClass</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#aa45791b7a34c31f98cfa5b415feda4b7">OutputCodeIntf::endFontClass</a>.</p>

</div>
</div>

### endSpecialComment() {#a4b1670c0ebaeda05f89224f58230f497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::endSpecialComment ()</td>
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



<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b1670c0ebaeda05f89224f58230f497">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4b1670c0ebaeda05f89224f58230f497">endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a9d22e7938c8ed39fd32ccac1339c3508">OutputCodeIntf::endSpecialComment</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a9d22e7938c8ed39fd32ccac1339c3508">OutputCodeIntf::endSpecialComment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>.</p>

</div>
</div>

### get() {#a3320211f0fe2d7cdcced9f93ccd8ab61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * OutputCodeList::get (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</td>
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

<p>Returns a pointer to a specific generator in the list.</p>

<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3320211f0fe2d7cdcced9f93ccd8ab61">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T *<a href="#a3320211f0fe2d7cdcced9f93ccd8ab61">get</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()==o) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(e.intf.get()); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>

</div>
</div>

### id() {#a6fdb262f6dcf3dc188a8c91814e9cba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int OutputCodeList::id ()</td>
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



<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a>; }</span></span></div>

</div>


<p>Reference <a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a>.</p>


<p>Referenced by <a href="#ac2ca8e5197d97fe6e8650a1949457ac0">setId</a> and <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a9fabdb64f4fd1b5a5fded9d7dac90c3b">TooltipManager::writeTooltips</a>.</p>

</div>
</div>

### setEnabledFiltered() {#aa698fb8d956eefe27034d2030751a002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::setEnabledFiltered (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o, bool enabled)</td>
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

<p>Enable or disable a specific generator.</p>

<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa698fb8d956eefe27034d2030751a002">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa698fb8d956eefe27034d2030751a002">setEnabledFiltered</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> enabled)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()==o) e.enabled = enabled;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>

</div>
</div>

### setId() {#ac2ca8e5197d97fe6e8650a1949457ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::setId (int id)</td>
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



<p>Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2ca8e5197d97fe6e8650a1949457ac0">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac2ca8e5197d97fe6e8650a1949457ac0">setId</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">) { <a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a> = <a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a>;   }</span></span></div>

</div>


<p>References <a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a> and <a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a>.</p>

</div>
</div>

### setStripIndentAmount() {#a7bc8bc3fc3e31c071445debd32a564ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::setStripIndentAmount (size_t amount)</td>
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



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bc8bc3fc3e31c071445debd32a564ed">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bc8bc3fc3e31c071445debd32a564ed">setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> amount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#ae8a406b182a468501ad1917116633ab0">OutputCodeIntf::setStripIndentAmount</a>,amount); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#ae8a406b182a468501ad1917116633ab0">OutputCodeIntf::setStripIndentAmount</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>.</p>

</div>
</div>

### startCodeFragment() {#ae6c741566f88d0cdbf6bdfceba362c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6c741566f88d0cdbf6bdfceba362c5d">278</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae6c741566f88d0cdbf6bdfceba362c5d">startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a58d79ca11fffa10472ef58b269541011">OutputCodeIntf::startCodeFragment</a>,style); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a58d79ca11fffa10472ef58b269541011">OutputCodeIntf::startCodeFragment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6d391007591f277cd73420b77403666d">writeXMLCodeBlock</a>.</p>

</div>
</div>

### startCodeLine() {#aa09941fc041983198d326b3b7cdc4795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::startCodeLine (int lineNr)</td>
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



<p>Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa09941fc041983198d326b3b7cdc4795">263</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa09941fc041983198d326b3b7cdc4795">startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a3fb3a11dd284ab1480d99c95ae0fb091">OutputCodeIntf::startCodeLine</a>,lineNr); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a3fb3a11dd284ab1480d99c95ae0fb091">OutputCodeIntf::startCodeLine</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>.</p>

</div>
</div>

### startFold() {#ac8fb201274cdd71281a93021e2d003d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::startFold (int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; startMarker, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; endMarker)</td>
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



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8fb201274cdd71281a93021e2d003d4">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8fb201274cdd71281a93021e2d003d4">startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;startMarker, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;endMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a5f11bd7fc9a1ec38e3221a159243b5a4">OutputCodeIntf::startFold</a>,lineNr,startMarker,endMarker); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a5f11bd7fc9a1ec38e3221a159243b5a4">OutputCodeIntf::startFold</a>.</p>

</div>
</div>

### startFontClass() {#ad5f1dacf0a9323f4471c33f81c1319d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; c)</td>
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



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5f1dacf0a9323f4471c33f81c1319d9">269</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad5f1dacf0a9323f4471c33f81c1319d9">startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a751c49686bddc0439d4b96128ac75695">OutputCodeIntf::startFontClass</a>,c); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a751c49686bddc0439d4b96128ac75695">OutputCodeIntf::startFontClass</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>.</p>

</div>
</div>

### startSpecialComment() {#a639977987188046433fd28e1bc9a766c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::startSpecialComment ()</td>
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



<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a639977987188046433fd28e1bc9a766c">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a639977987188046433fd28e1bc9a766c">startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a2105904a9b7d083f83bde63158363b63">OutputCodeIntf::startSpecialComment</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a2105904a9b7d083f83bde63158363b63">OutputCodeIntf::startSpecialComment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>.</p>

</div>
</div>

### stripCodeComments() {#aebb587648d0dbbfec75c7b7ffc6873ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::stripCodeComments (bool b)</td>
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



<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebb587648d0dbbfec75c7b7ffc6873ba">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#abd954df01d21e1f9aa5f8682d24b9a3a">OutputCodeIntf::stripCodeComments</a>,b); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#abd954df01d21e1f9aa5f8682d24b9a3a">OutputCodeIntf::stripCodeComments</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a> and <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>.</p>

</div>
</div>

### writeCodeAnchor() {#a759bd4d05586bd782adfd25ce635079f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a759bd4d05586bd782adfd25ce635079f">275</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a759bd4d05586bd782adfd25ce635079f">writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a34a19054dbac04d31197d5f18c23922d">OutputCodeIntf::writeCodeAnchor</a>,name); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a34a19054dbac04d31197d5f18c23922d">OutputCodeIntf::writeCodeAnchor</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>.</p>

</div>
</div>

### writeCodeLink() {#a4fb20173014b60bceb6f75a621749f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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



<p>Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fb20173014b60bceb6f75a621749f73">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4fb20173014b60bceb6f75a621749f73">writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a5a3e141983bf4260e82411d8c7be7d55">OutputCodeIntf::writeCodeLink</a>,type,ref,file,anchor,name,tooltip); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a5a3e141983bf4260e82411d8c7be7d55">OutputCodeIntf::writeCodeLink</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a> and <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aefd632b8f888c312d4d67dffa15f5669">writeMultiLineCodeLink</a>.</p>

</div>
</div>

### writeLineNumber() {#ad08d11446544b377ebb9a66f76e0a1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int lineNumber, bool writeLineAnchor)</td>
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



<p>Definition at line 255 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad08d11446544b377ebb9a66f76e0a1ad">255</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad08d11446544b377ebb9a66f76e0a1ad">writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNumber, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a0f83ec2ce57b0584b7b9e9cbbdc31b94">OutputCodeIntf::writeLineNumber</a>,ref,file,anchor,lineNumber,writeLineAnchor); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a0f83ec2ce57b0584b7b9e9cbbdc31b94">OutputCodeIntf::writeLineNumber</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>.</p>

</div>
</div>

### writeTooltip() {#a81f3db752795807f3c67e25f6fdcb081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp; docInfo, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; decl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; desc, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; defInfo, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; declInfo)</td>
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



<p>Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81f3db752795807f3c67e25f6fdcb081">259</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a81f3db752795807f3c67e25f6fdcb081">writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;docInfo, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;decl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;desc, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;defInfo, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;declInfo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputcodeintf/#a86646b8aa6afd124317929d823b08fc4">OutputCodeIntf::writeTooltip</a>,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,docInfo,decl,desc,defInfo,declInfo); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputcodeintf/#a86646b8aa6afd124317929d823b08fc4">OutputCodeIntf::writeTooltip</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a9fabdb64f4fd1b5a5fded9d7dac90c3b">TooltipManager::writeTooltips</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### foreach() {#a83e76d5788ad3b3cc9142cbcc67edca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeList::foreach (void(OutputCodeIntf::*)(Ts...) methodPtr, As &amp;&amp;... args)</td>
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



<p>Definition at line 292 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83e76d5788ad3b3cc9142cbcc67edca6">292</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a>::*methodPtr)(Ts...),As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.enabled)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">          (e.intf.get()-&gt;*methodPtr)(std::forward&lt;As&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_id {#a7d78b59a476511a0e4d91cc2d175a769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int OutputCodeList::m_id = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d78b59a476511a0e4d91cc2d175a769">304</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7d78b59a476511a0e4d91cc2d175a769">m_id</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a> and <a href="#ac2ca8e5197d97fe6e8650a1949457ac0">setId</a>.</p>

</div>
</div>

### m\_outputCodeList {#a1b66e22d9c49abb5cec665038904357b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;OutputCodeElem&gt; OutputCodeList::m_outputCodeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b66e22d9c49abb5cec665038904357b">303</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;OutputCodeElem&gt; <a href="#a1b66e22d9c49abb5cec665038904357b">m_outputCodeList</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a140918bf6841d5fa572a58a7a59eece9">add</a>, <a href="#a60b7d69b02fe400d0111a3321c9f0265">add</a>, <a href="#a8f3366931e582bd83073396e0a95ce7c">clear</a>, <a href="#a83e76d5788ad3b3cc9142cbcc67edca6">foreach</a>, <a href="#a3320211f0fe2d7cdcced9f93ccd8ab61">get</a> and <a href="#aa698fb8d956eefe27034d2030751a002">setEnabledFiltered</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
