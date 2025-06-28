---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/filtercache
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `FilterCache` Class Reference



## Declaration

<div class="doxyDeclaration">
class FilterCache { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> = std::vector&lt; size_t &gt;</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d001d30e4d16855d3656989947df29">getFileContents</a> (const QCString &amp;fileName, size_t startLine, size_t endLine, std::string &amp;str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a> (const QCString &amp;fileName, const QCString &amp;filter, size_t startLine, size_t endLine, std::string &amp;str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a> (const QCString &amp;fileName, size_t startLine, size_t endLine, std::string &amp;str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1db762aaf71f44e596c234a11248c0">compileLineOffsets</a> (const QCString &amp;fileName, const std::string &amp;str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; size_t, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a> (const LineOffsets &amp;lineOffsets, size_t startLine, size_t endLine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a> (std::string &amp;str, const QCString &amp;fileName, size_t startLine, size_t endLine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a> (std::string &amp;str, const QCString &amp;fileName, size_t startOffset, size_t size=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem">FilterCacheItem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m_cache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m_mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9330d2904c228992b599ec62cf3442e0">m_endPos</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/filtercache">FilterCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75634f3ff0bcd32cd82ba3d0fc8afbb3">instance</a> ()</td>
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



<p><a href="/web-doxygen/docs/api/classes/cache">Cache</a> for storing the result of filtering a file</p>

<p>Definition at line 530 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxySectionDef">

## Private Member Typedefs

### LineOffsets {#a125fac6149a9636b3f8343b05ca24ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using FilterCache::LineOffsets =  std::vector&lt;size_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00538">538</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a125fac6149a9636b3f8343b05ca24ea9">538</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> = std::vector&lt;size_t&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### FilterCache() {#a01f051d4654d2e0d8bb344cf3111b4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilterCache::FilterCache ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00722">722</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01f051d4654d2e0d8bb344cf3111b4be">722</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a>() : <a href="#a9330d2904c228992b599ec62cf3442e0">m_endPos</a>(0) { }</span></span></div>

</div>


Reference <a href="#a9330d2904c228992b599ec62cf3442e0">m&#95;endPos</a>.

Referenced by <a href="#a75634f3ff0bcd32cd82ba3d0fc8afbb3">instance</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFileContents() {#aa5d001d30e4d16855d3656989947df29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FilterCache::getFileContents (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, size_t startLine, size_t endLine, std::string &amp; str)</td>
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



<p>collects the part of file <em>fileName</em> starting at <em>startLine</em> and ending at <em>endLine</em> into buffer <em>str</em>. Applies filtering if FILTER_SOURCE_FILES is enabled and the file extension matches a filter. Caches file information so that subsequent extraction of blocks from the same file can be performed efficiently</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00547">547</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5d001d30e4d16855d3656989947df29">547</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa5d001d30e4d16855d3656989947df29">getFileContents</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLine, std::string &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> filterSourceFiles = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FILTER_SOURCE_FILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> filter = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>(fileName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> usePipe = !filter.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; filterSourceFiles;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> usePipe ? <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>(fileName,filter,startLine,endLine,str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                     : <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a>(fileName,startLine,endLine,str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a>, <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### compileLineOffsets() {#a9e1db762aaf71f44e596c234a11248c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FilterCache::compileLineOffsets (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const std::string &amp; str)</td>
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



<p>computes the starting offset for each line for file <em>fileName</em>, whose contents should already be stored in buffer <em>str</em>.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00666">666</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e1db762aaf71f44e596c234a11248c0">666</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e1db762aaf71f44e596c234a11248c0">compileLineOffsets</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// line 1 (index 0) is at offset 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.emplace(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a>{0}).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.data();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; c!=0) p++; </span><span class="doxyHighlightComment">// search until end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c!=0) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;second.push_back(p-str.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m&#95;lineOffsets</a>.

Referenced by <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>.
</div>
</div>

### getFileContentsDisk() {#a5730ddb0e69085c4031028a2eb383f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FilterCache::getFileContentsDisk (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, size_t startLine, size_t endLine, std::string &amp; str)</td>
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



<p>reads the fragment start at <em>startLine</em> and ending at <em>endLine</em> from file <em>fileName</em> into buffer <em>str</em></p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00640">640</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5730ddb0e69085c4031028a2eb383f14">640</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLine,std::string &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_lock&lt;std::mutex&gt; lock(<a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// normal file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("getFileContents(%s): no filter\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.find(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it == <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.end()) </span><span class="doxyHighlightComment">// new file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// read file completely into str buffer</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>(str,fileName,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// shrink buffer to [startLine..endLine] part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>(str,fileName,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// file already processed before</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">        lock.unlock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> [ startLineOffset, fragmentSize] = <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>(it-&gt;second,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("%s: existing file [%zu-%zu] -&gt; start=%zu size=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//    qPrint(fileName),startLine,endLine,startLineOffset,fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>(str,fileName,startLineOffset,fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>, <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m&#95;lineOffsets</a>, <a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m&#95;mutex</a>, <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>, <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#aa5d001d30e4d16855d3656989947df29">getFileContents</a>.
</div>
</div>

### getFileContentsPipe() {#ad313a32a960f39f775ebb6d5bc8c5fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FilterCache::getFileContentsPipe (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; filter, size_t startLine, size_t endLine, std::string &amp; str)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00556">556</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">556</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;filter,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLine,std::string &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_lock&lt;std::mutex&gt; lock(<a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m_cache</a>.find(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m_cache</a>.end()) </span><span class="doxyHighlightComment">// cache hit: reuse stored result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">        lock.unlock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> item = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("getFileContents(%s): cache hit\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// file already processed, get the results after filtering from the tmp file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>,0,</span><span class="doxyHighlightStringLiteral">"Reusing filter result for {} from {} at offset={} size={}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">               fileName,<a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>,item.filePos,item.fileSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it_off = <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.find(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">        assert(it_off!=<a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> [ startLineOffset, fragmentSize] = <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>(it_off-&gt;second,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("%s: existing file [%zu-%zu]-&gt;[%zu-%zu] size=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//    qPrint(fileName),startLine,endLine,startLineOffset,endLineOffset,fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>(str, <a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>.data(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                             item.filePos+startLineOffset, fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// cache miss: filter active but file not previously processed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("getFileContents(%s): cache miss\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// filter file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cmd=filter+</span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">+fileName+</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3">Debug::ExtCmd</a>,0,</span><span class="doxyHighlightStringLiteral">"Executing popen(`{}`)\n"</span><span class="doxyHighlight">,cmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">        FILE *f = <a href="/web-doxygen/docs/api/namespaces/portable/#a15b92ac03be9e8f4d95d5e881342d83c">Portable::popen</a>(cmd,</span><span class="doxyHighlightStringLiteral">"r"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// handle error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Error opening filter pipe command '{}'\n"</span><span class="doxyHighlight">,cmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">        FILE *bf = <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>,</span><span class="doxyHighlightStringLiteral">"a+b"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem">FilterCacheItem</a> item;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">        item.<a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a51a5eed73e6e5008821208437be7c088">filePos</a> = <a href="#a9330d2904c228992b599ec62cf3442e0">m_endPos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bf==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// handle error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Error opening filter database file {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/namespaces/portable/#a6cde8cab8c3dc3397ea5c6030fbf6e84">Portable::pclose</a>(f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// append the filtered output to the database file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!feof(f))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> blockSize = 4096;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[blockSize];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> bytesRead = fread(buf,1,blockSize,f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> bytesWritten = fwrite(buf,1,bytesRead,bf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bytesRead!=bytesWritten)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// handle error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to write to filter database {}. Wrote {} out of {} bytes\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>,bytesWritten,bytesRead);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/namespaces/portable/#a6cde8cab8c3dc3397ea5c6030fbf6e84">Portable::pclose</a>(f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">            fclose(bf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">          size+=bytesWritten;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">          str+=std::string_view(buf,bytesWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">        item.<a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a0c4e7b3028e05b8ad7b06e58436bf1b0">fileSize</a> = size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// add location entry to the dictionary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m_cache</a>.emplace(fileName.str(),item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>,0,</span><span class="doxyHighlightStringLiteral">"Storing new filter result for {} in {} at offset={} size={}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">               fileName,<a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>,item.<a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a51a5eed73e6e5008821208437be7c088">filePos</a>,item.<a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a0c4e7b3028e05b8ad7b06e58436bf1b0">fileSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// update end of file position</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9330d2904c228992b599ec62cf3442e0">m_endPos</a> += size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/namespaces/portable/#a6cde8cab8c3dc3397ea5c6030fbf6e84">Portable::pclose</a>(f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">        fclose(bf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// shrink buffer to [startLine..endLine] part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>(str,fileName,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3">Debug::ExtCmd</a>, <a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a51a5eed73e6e5008821208437be7c088">FilterCache::FilterCacheItem::filePos</a>, <a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem/#a0c4e7b3028e05b8ad7b06e58436bf1b0">FilterCache::FilterCacheItem::fileSize</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ab044e0b3e178d1ba542e38a9c206d57a">Doxygen::filterDBFileName</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>, <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>, <a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m&#95;cache</a>, <a href="#a9330d2904c228992b599ec62cf3442e0">m&#95;endPos</a>, <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m&#95;lineOffsets</a>, <a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m&#95;mutex</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a6cde8cab8c3dc3397ea5c6030fbf6e84">Portable::pclose</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a15b92ac03be9e8f4d95d5e881342d83c">Portable::popen</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>, <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#aa5d001d30e4d16855d3656989947df29">getFileContents</a>.
</div>
</div>

### getFragmentLocation() {#a2b04ae61006aa3e9ac0d44ded23f246d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; size_t, size_t &gt; FilterCache::getFragmentLocation (const <a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> &amp; lineOffsets, size_t startLine, size_t endLine)</td>
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



<p>Returns the byte offset and size within a file of a fragment given the array of line offsets and the start and end line of the fragment.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00682">682</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b04ae61006aa3e9ac0d44ded23f246d">682</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> &amp;lineOffsets,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLine) -&gt; std::tuple&lt;size_t,size_t&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(startLine &gt; 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(startLine &lt;= endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLineOffset = lineOffsets[std::min(startLine-1,lineOffsets.size()-1)];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLineOffset   = lineOffsets[std::min(endLine,    lineOffsets.size()-1)];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(startLineOffset &lt;= endLineOffset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> fragmentSize = endLineOffset-startLineOffset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::tie(startLineOffset,fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>


Referenced by <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a>, <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a> and <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>.
</div>
</div>

### readFragmentFromFile() {#a7c86623ce94e7e3129386f2c8553fb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FilterCache::readFragmentFromFile (std::string &amp; str, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, size_t startOffset, size_t size=0)</td>
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



<p>Reads the fragment start at byte offset <em>startOffset</em> of file <em>fileName</em> into buffer <em>str</em>. Result will be a null terminated. If size==0 the whole file will be read and startOffset is ignored. If size&gt;0, size bytes will be read.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00713">713</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c86623ce94e7e3129386f2c8553fb16">713</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c86623ce94e7e3129386f2c8553fb16">readFragmentFromFile</a>(std::string &amp;str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startOffset,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">      std::ifstream ifs = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(fileName,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size==0) { startOffset=0; size = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ifs.tellg()); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      ifs.seekg(startOffset, std::ios::beg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      str.resize(size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">      ifs.read(str.data(), size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>.

Referenced by <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a> and <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>.
</div>
</div>

### shrinkBuffer() {#a11addfe71baa15d57b1423b4aab53f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FilterCache::shrinkBuffer (std::string &amp; str, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, size_t startLine, size_t endLine)</td>
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



<p>Shrinks buffer <em>str</em> which should hold the contents of <em>fileName</em> to the fragment starting a line <em>startLine</em> and ending at line <em>endLine</em></p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00696">696</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11addfe71baa15d57b1423b4aab53f76">696</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>(std::string &amp;str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// compute offsets from start for each line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9e1db762aaf71f44e596c234a11248c0">compileLineOffsets</a>(fileName,str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.find(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(it!=<a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a125fac6149a9636b3f8343b05ca24ea9">LineOffsets</a> &amp;lineOffsets = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> [ startLineOffset, fragmentSize] = <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>(lineOffsets,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("%s: new file [%zu-%zu]-&gt;[%zu-%zu] size=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(fileName),startLine,endLine,startLineOffset,endLineOffset,fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">      str.erase(0,startLineOffset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">      str.resize(fragmentSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a9e1db762aaf71f44e596c234a11248c0">compileLineOffsets</a>, <a href="#a2b04ae61006aa3e9ac0d44ded23f246d">getFragmentLocation</a>, <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m&#95;lineOffsets</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a> and <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;cache {#ad92cbee1c6a87517ee25ce8fc5fa9657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,FilterCacheItem&gt; FilterCache::m_cache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00723">723</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">723</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,FilterCacheItem&gt; <a href="#ad92cbee1c6a87517ee25ce8fc5fa9657">m_cache</a>;</span></span></div>

</div>


Referenced by <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>.
</div>
</div>

### m&#95;endPos {#a9330d2904c228992b599ec62cf3442e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t FilterCache::m_endPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00726">726</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9330d2904c228992b599ec62cf3442e0">726</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a9330d2904c228992b599ec62cf3442e0">m_endPos</a>;</span></span></div>

</div>


Referenced by <a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a> and <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>.
</div>
</div>

### m&#95;lineOffsets {#a3772d8fa456dcd1aa7fa7719552d06e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,LineOffsets&gt; FilterCache::m_lineOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00724">724</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3772d8fa456dcd1aa7fa7719552d06e1">724</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,LineOffsets&gt; <a href="#a3772d8fa456dcd1aa7fa7719552d06e1">m_lineOffsets</a>;</span></span></div>

</div>


Referenced by <a href="#a9e1db762aaf71f44e596c234a11248c0">compileLineOffsets</a>, <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a>, <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a> and <a href="#a11addfe71baa15d57b1423b4aab53f76">shrinkBuffer</a>.
</div>
</div>

### m&#95;mutex {#afd73c9ef7ca1d08c6c051f3076b44a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex FilterCache::m_mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00725">725</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">725</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::mutex <a href="#afd73c9ef7ca1d08c6c051f3076b44a1f">m_mutex</a>;</span></span></div>

</div>


Referenced by <a href="#a5730ddb0e69085c4031028a2eb383f14">getFileContentsDisk</a> and <a href="#ad313a32a960f39f775ebb6d5bc8c5fe1">getFileContentsPipe</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a75634f3ff0bcd32cd82ba3d0fc8afbb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilterCache &amp; FilterCache::instance ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/definition-cpp/#l00541">541</a> of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75634f3ff0bcd32cd82ba3d0fc8afbb3">729</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a> &amp;<a href="#a75634f3ff0bcd32cd82ba3d0fc8afbb3">FilterCache::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a01f051d4654d2e0d8bb344cf3111b4be">FilterCache</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
