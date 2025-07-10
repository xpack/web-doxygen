---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/dir-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `dir.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "filesystem.hpp"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include &lt;utility&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/direntry/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/dir/private">Private</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9285cecfcff40959eed73e1da7d139da">operator==</a> (const DirIterator &amp;it1, const DirIterator &amp;it2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde2fab844e4f384c5d715f06f0835f4">operator!=</a> (const DirIterator &amp;it1, const DirIterator &amp;it2)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c94b68ae7d5509e621425954c7fc50">begin</a> (DirIterator it)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0550a128905c4e07b633d437992b002">end</a> (const DirIterator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b11506131606fe77129beddff464004">correctPath</a> (std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f918755b601cf4bffca775992e6fb90">NOMINMAX</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7bef5d85e3dcd73eef56ad39ffc84a9">WIN32_LEAN_AND_MEAN</a></td>
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

## Operators

### operator!=() {#acde2fab844e4f384c5d715f06f0835f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator!= (const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it1, const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/diriterator/#acde2fab844e4f384c5d715f06f0835f4">165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acde2fab844e4f384c5d715f06f0835f4">operator!=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it1.<a href="/web-doxygen/docs/api/classes/diriterator/#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it!=it2.<a href="/web-doxygen/docs/api/classes/diriterator/#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator==() {#a9285cecfcff40959eed73e1da7d139da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator== (const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it1, const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/diriterator/#a9285cecfcff40959eed73e1da7d139da">160</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9285cecfcff40959eed73e1da7d139da">operator==</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it1.<a href="/web-doxygen/docs/api/classes/diriterator/#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it == it2.<a href="/web-doxygen/docs/api/classes/diriterator/#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### begin() {#ab6c94b68ae7d5509e621425954c7fc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator begin (<a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> it)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/diriterator/#ab6c94b68ae7d5509e621425954c7fc50">170</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> <a href="#ab6c94b68ae7d5509e621425954c7fc50">begin</a>(<a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> it) </span><span class="doxyHighlightKeyword">noexcept</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#abe5bc298b8ac3b911af947e2b29089f5">FlowChart::buildCommentNodes</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/classes/memberlists/#a4c6708898611587ed51cf6c1a2622c52">MemberLists::get</a>, <a href="/web-doxygen/docs/api/classes/examplelist/#a461e72c8f6d52cf93b0c4db33d6bda8b">ExampleList::inSort</a>, <a href="/web-doxygen/docs/api/classes/htmlattriblist/#ac7c837fb5c6a666618137b335fe89760">HtmlAttribList::mergeAttribute</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/portable-cpp/#a9ecb00561bffb0bffa3cce647d399c6f">portable_memmem</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>.</p>

</div>
</div>

### correctPath() {#a0b11506131606fe77129beddff464004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void correctPath (std::string &amp; s)</td>
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



<p>Definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b11506131606fe77129beddff464004">244</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b11506131606fe77129beddff464004">correctPath</a>(std::string &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  std::replace( s.begin(), s.end(), </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">, </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">Dir::absPath</a>, <a href="/web-doxygen/docs/api/classes/dir/#ab25b50ffd43d7163ea07a6625dfe9088">Dir::cleanDirPath</a>, <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a> and <a href="/web-doxygen/docs/api/classes/dir/#a9648972511650311756008587b2ef819">Dir::filePath</a>.</p>

</div>
</div>

### end() {#ad0550a128905c4e07b633d437992b002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator end (const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/diriterator/#ad0550a128905c4e07b633d437992b002">175</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> <a href="#ad0550a128905c4e07b633d437992b002">end</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;) </span><span class="doxyHighlightKeyword">noexcept</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/diriterator/#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docgroup/#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab60f2f0badb4e5ea7ab8257b599dc267">addToIndices</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a7610569d96adb6bd19ed159a5f53a26c">DocGroup::close</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge/#a72ac56ac966b6ab1f983c728e99f9608">DotGroupCollaboration::Edge::Edge</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0a8ffacc302979f9f812ab6608967287">extractDirection</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a87fd251583954635281c516ceee7fd34">findAndRemoveWord</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>, <a href="/web-doxygen/docs/api/classes/memberlists/#a4c6708898611587ed51cf6c1a2622c52">MemberLists::get</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2f61e0684c24af28ef2f9955e04aa6d7">getTemplateArgumentsInName</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/examplelist/#a461e72c8f6d52cf93b0c4db33d6bda8b">ExampleList::inSort</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#ac6f893b36841e3cf90bf79cc6d992ee5">vhdl::parser::VhdlParserTokenManager::jjKindsForStateVector</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/htmlattriblist/#ac7c837fb5c6a666618137b335fe89760">HtmlAttribList::mergeAttribute</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a9cb5ab2169da2f5bf14816e9c10e8290">DocGroup::open</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#ac0a9e3273eb76713a9e197d5be61e11a">Markdown::Private::processInline</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af428b9307683dc2c090f7d837138b438">QCString::quoted</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2cc67737d5d2452bb74b4968bb24a00c">split</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a848aaabaf4d7b73351e6850d05254d99">stripKeyword</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a6444196e54d0b736cef5c9edd8c262d9">QCString::stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae241503d7e4252f10ab58d6bacc87973">writeMarkerList</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### NOMINMAX {#a9f918755b601cf4bffca775992e6fb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NOMINMAX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f918755b601cf4bffca775992e6fb90">16</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NOMINMAX</span></span></div>

</div>

</div>
</div>

### WIN32\_LEAN\_AND\_MEAN {#ac7bef5d85e3dcd73eef56ad39ffc84a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define WIN32_LEAN_AND_MEAN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7bef5d85e3dcd73eef56ad39ffc84a9">17</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define WIN32_LEAN_AND_MEAN</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
