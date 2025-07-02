---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/markdownoutlineparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `MarkdownOutlineParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class MarkdownOutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/markdown-h">src/markdown.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract interface for outline parsers. <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb5ef90db1a3302c0bc0e06e684d880">MarkdownOutlineParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7d33c84a9bbe78b498a458ae7cc861">~MarkdownOutlineParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb95204f0f91c085e6a9808efb2ebdc">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#a0cb95204f0f91c085e6a9808efb2ebdc">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69493ea3c18566cbc3813c1b7a787321">needsPreprocessing</a> (const QCString &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a69493ea3c18566cbc3813c1b7a787321">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac673a30488ede0451a6a28601ece560f">parsePrototype</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Callback function called by the comment block scanner. <a href="#ac673a30488ede0451a6a28601ece560f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/markdownoutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a></td>
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


Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.

<div class="doxySectionDef">

## Public Constructors

### MarkdownOutlineParser() {#a8fb5ef90db1a3302c0bc0e06e684d880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MarkdownOutlineParser::MarkdownOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3621 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8fb5ef90db1a3302c0bc0e06e684d880">3621</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a8fb5ef90db1a3302c0bc0e06e684d880">MarkdownOutlineParser::MarkdownOutlineParser</a>() : <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/markdownoutlineparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3622</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3623</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MarkdownOutlineParser() {#a6b7d33c84a9bbe78b498a458ae7cc861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MarkdownOutlineParser::~MarkdownOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3625 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b7d33c84a9bbe78b498a458ae7cc861">3625</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a6b7d33c84a9bbe78b498a458ae7cc861">MarkdownOutlineParser::~MarkdownOutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3626</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3627</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a69493ea3c18566cbc3813c1b7a787321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MarkdownOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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

Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser.


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput()</a>
</dd>
</dl>


Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a69493ea3c18566cbc3813c1b7a787321">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a69493ea3c18566cbc3813c1b7a787321">needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.
</div>
</div>

### parseInput() {#a0cb95204f0f91c085e6a9808efb2ebdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MarkdownOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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

Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription">The full name of the file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileBuf</td>
<td class="doxyParamItemDescription">The contents of the file (zero terminated).</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] root</td>
<td class="doxyParamItemDescription">The root of the tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *nodes representing the information extracted from the file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] clangParser</td>
<td class="doxyParamItemDescription">The clang translation unit parser object or nullptr if disabled.</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3629 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cb95204f0f91c085e6a9808efb2ebdc">3629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3630</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3631</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3632</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a>* </span><span class="doxyHighlightComment">/*clangParser*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3633</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3634</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; current = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3635</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prepend = 0; </span><span class="doxyHighlightComment">// number of empty lines in front</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3636</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;lang = SrcLangExt::Markdown;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3637</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;fileName = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3638</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;docFile  = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3639</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;docLine  = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3640</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> docs = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>(fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3642</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>,0,</span><span class="doxyHighlightStringLiteral">"======== Markdown =========\n---- input ------- \n{}\n"</span><span class="doxyHighlight">,fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3643</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3644</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> markdown(fileName,1,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3645</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isIdGenerated = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3646</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title = markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">extractPageTitle</a>(docs, </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, prepend, isIdGenerated).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3647</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> generatedId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isIdGenerated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3649</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3650</span><span class="doxyLineContent"><span class="doxyHighlight">    generatedId = id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3651</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3652</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3653</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indentLevel=title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? 0 : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3654</span><span class="doxyLineContent"><span class="doxyHighlight">  markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ab176950dfe9ce90a45af5db61b5acf88">setIndentLevel</a>(indentLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3655</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3656</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn      = fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3657</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> titleFn = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>(fn,<a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(fn));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3658</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mdfileAsMainPage = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(USE_MDFILE_AS_MAINPAGE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3659</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mdFileNameId = <a href="/web-doxygen/docs/api/files/src/markdown-h/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> wasEmpty = </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3661</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (wasEmpty) </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = mdFileNameId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3662</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relFileName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3663</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSubdirDocs = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(IMPLICIT_DIR_DOCS) &amp;&amp; relFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"/readme.md"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>(docs))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3665</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">ExplicitPageResult::notExplicit</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3667</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdfileAsMainPage.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3668</span><span class="doxyLineContent"><span class="doxyHighlight">          (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>()==<a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a>(mdfileAsMainPage.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()).<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>()) </span><span class="doxyHighlightComment">// file reference with path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3669</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3670</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3671</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@ianchor{"</span><span class="doxyHighlight"> + title + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight"> + </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3672</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@mainpage "</span><span class="doxyHighlight">+title+</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3673</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3674</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">==</span><span class="doxyHighlightStringLiteral">"mainpage"</span><span class="doxyHighlight"> || </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">==</span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3675</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3676</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) title = titleFn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3677</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@ianchor{"</span><span class="doxyHighlight"> + title + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight"> + </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3678</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@mainpage "</span><span class="doxyHighlight">+title+</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3679</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3680</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isSubdirDocs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3681</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3682</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!generatedId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3683</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3684</span><span class="doxyLineContent"><span class="doxyHighlight">          docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@section "</span><span class="doxyHighlight"> + generatedId + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + title + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3685</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3686</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@dir\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3687</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3688</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3689</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3690</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3691</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3692</span><span class="doxyLineContent"><span class="doxyHighlight">          title = titleFn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3693</span><span class="doxyLineContent"><span class="doxyHighlight">          prepend = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3694</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3695</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wasEmpty)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3696</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3697</span><span class="doxyLineContent"><span class="doxyHighlight">          docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@ianchor{"</span><span class="doxyHighlight"> + title + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight"> + </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> + </span><span class="doxyHighlightStringLiteral">"\\ilinebr @ianchor{"</span><span class="doxyHighlight"> + relFileName + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight"> + mdFileNameId + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3698</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3699</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!generatedId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3700</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3701</span><span class="doxyLineContent"><span class="doxyHighlight">          docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@ianchor "</span><span class="doxyHighlight"> +  generatedId + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3702</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3703</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE)==MARKDOWN_ID_STYLE_t::GITHUB)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3704</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3705</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> autoId = <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>().<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">generate</a>(title.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3706</span><span class="doxyLineContent"><span class="doxyHighlight">          docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@ianchor{"</span><span class="doxyHighlight"> + title + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight"> +  autoId + </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3707</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3708</span><span class="doxyLineContent"><span class="doxyHighlight">        docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@page "</span><span class="doxyHighlight">+</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+title+</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3709</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3710</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; prepend; i++) docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3711</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">ExplicitPageResult::explicitPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3713</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3714</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// look for `@page label My Title\n` and capture `label` (match[1]) and ` My Title` (match[2])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3715</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"([ ]*[\\@]page\s+(\a[\w-]*)(\s*[^\n]*)\n)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3716</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">        <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3717</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">        std::string s = docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3718</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,match,re))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3719</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3720</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> orgLabel    = match[1].str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3721</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> orgTitle    = match[2].str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3722</span><span class="doxyLineContent"><span class="doxyHighlight">          orgTitle = orgTitle.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3723</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> newLabel    = <a href="/web-doxygen/docs/api/files/src/markdown-h/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3724</span><span class="doxyLineContent"><span class="doxyHighlight">          docs = docs.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(match[1].position())+               </span><span class="doxyHighlightComment">// part before label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3725</span><span class="doxyLineContent"><span class="doxyHighlight">                 newLabel+                                     </span><span class="doxyHighlightComment">// new label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3726</span><span class="doxyLineContent"><span class="doxyHighlight">                 match[2].str()+                               </span><span class="doxyHighlightComment">// part between orgLabel and \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3727</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"\\ilinebr @ianchor{"</span><span class="doxyHighlight"> + orgTitle + </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">+orgLabel+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">+           </span><span class="doxyHighlightComment">// add original anchor plus \n of above</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3728</span><span class="doxyLineContent"><span class="doxyHighlight">                 docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-match.length());     </span><span class="doxyHighlightComment">// add remainder of docs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3729</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3730</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3731</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">ExplicitPageResult::explicitMainPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3734</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">ExplicitPageResult::explicitOtherPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3736</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3738</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3739</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>-&gt;commentScanner.enterFile(fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3740</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3741</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsEntry = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> position=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3743</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> guards;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3744</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> processedDocs = markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">process</a>(docs,lineNr,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3745</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>-&gt;commentScanner.parseCommentBlock(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3746</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3747</span><span class="doxyLineContent"><span class="doxyHighlight">        current.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3748</span><span class="doxyLineContent"><span class="doxyHighlight">        processedDocs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3749</span><span class="doxyLineContent"><span class="doxyHighlight">        fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3750</span><span class="doxyLineContent"><span class="doxyHighlight">        lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3751</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,     </span><span class="doxyHighlightComment">// isBrief</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3752</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,     </span><span class="doxyHighlightComment">// javadoc autobrief</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3753</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,     </span><span class="doxyHighlightComment">// inBodyDocs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3754</span><span class="doxyLineContent"><span class="doxyHighlight">        prot,      </span><span class="doxyHighlightComment">// protection</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3755</span><span class="doxyLineContent"><span class="doxyHighlight">        position,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3756</span><span class="doxyLineContent"><span class="doxyHighlight">        needsEntry,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3757</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3758</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;guards</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3759</span><span class="doxyLineContent"><span class="doxyHighlight">        ))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3760</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3761</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3762</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3763</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> docFile = current-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3764</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndRefresh(current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3765</span><span class="doxyLineContent"><span class="doxyHighlight">      current-&gt;lang = SrcLangExt::Markdown;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3766</span><span class="doxyLineContent"><span class="doxyHighlight">      current-&gt;docFile = docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3767</span><span class="doxyLineContent"><span class="doxyHighlight">      current-&gt;docLine = lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3768</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3769</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3770</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3771</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3772</span><span class="doxyLineContent"><span class="doxyHighlight">    root-&gt;moveToSubEntryAndKeep(current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3773</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3774</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>-&gt;commentScanner.leaveFile(fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3775</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">explicitMainPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">explicitOtherPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">explicitPage</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>, <a href="/web-doxygen/docs/api/files/src/markdown-h/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">notExplicit</a>, <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ab176950dfe9ce90a45af5db61b5acf88">Markdown::setIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.
</div>
</div>

### parsePrototype() {#ac673a30488ede0451a6a28601ece560f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MarkdownOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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

Callback function called by the comment block scanner.


It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.

Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3777 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac673a30488ede0451a6a28601ece560f">3777</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac673a30488ede0451a6a28601ece560f">MarkdownOutlineParser::parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3778</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3779</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>-&gt;getOutlineParser(</span><span class="doxyHighlightStringLiteral">"*.cpp"</span><span class="doxyHighlight">)-&gt;parsePrototype(text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3780</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ae7e3150da2e63dfdddf40fbec779b9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; MarkdownOutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7e3150da2e63dfdddf40fbec779b9b5">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ae7e3150da2e63dfdddf40fbec779b9b5">p</a>;</span></span></div>

</div>


Referenced by <a href="#a8fb5ef90db1a3302c0bc0e06e684d880">MarkdownOutlineParser</a> and <a href="#a0cb95204f0f91c085e6a9808efb2ebdc">parseInput</a>.
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
