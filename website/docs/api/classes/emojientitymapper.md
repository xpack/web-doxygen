---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/emojientitymapper
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `EmojiEntityMapper` Class Reference

Singleton helper class to map emoji entities to other formats. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class EmojiEntityMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/emoji-h">src/emoji.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ef574821b28aefb585a4a135e41dd7">~EmojiEntityMapper</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a> (int index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Access routine to the name of the Emoji entity. <a href="#a33137ef11c5d63f6f7d7a27c01db943e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a> (int index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Access routine to the unicode sequence for the Emoji entity. <a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a564160bf157ebe6a13531392bb48b">writeEmojiFile</a> (TextStream &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Writes the list of supported emojis to the given file. <a href="#aa3a564160bf157ebe6a13531392bb48b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index</a> (const std::string &amp;symName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a code for the requested Emoji entity name. <a href="#a8f20a25544d61a753eaf73d2618c9c88">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/emojientitymapper">EmojiEntityMapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4ebc91738fb8f8af7459346a86f49b">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the one and only instance of the Emoji entity mapper. <a href="#a6b4ebc91738fb8f8af7459346a86f49b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/emojientitymapper">EmojiEntityMapper</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd0bd31e345895d4f8fd2d864e3d3d5">s_instance</a> = nullptr</td>
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

Singleton helper class to map emoji entities to other formats.

Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>.

<div class="doxySectionDef">

## Private Constructors

### EmojiEntityMapper() {#aa0e24fab34771f5263da10a2fc3c593e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmojiEntityMapper::EmojiEntityMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 1960 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0e24fab34771f5263da10a2fc3c593e">1960</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper::EmojiEntityMapper</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a>; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a>.emplace(<a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>[i].<a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a>, </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a6296d06ea0d5be85d060dac04b76d4f7">g_numEmojiCompatibilityEntities</a>; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ii = <a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index</a>(<a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>[i].newName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii != -1) <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a>.emplace(<a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>[i].oldName, ii);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a872534923eff1e9e95b0816e9f2a30b7">g\_emojiCompatibilityEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g\_emojiEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a6296d06ea0d5be85d060dac04b76d4f7">g\_numEmojiCompatibilityEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g\_numEmojiEntities</a>, <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m\_name2symGh</a>, <a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a> and <a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index</a>.

Referenced by <a href="#a6b4ebc91738fb8f8af7459346a86f49b">instance</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~EmojiEntityMapper() {#aa9ef574821b28aefb585a4a135e41dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmojiEntityMapper::~EmojiEntityMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 1973 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9ef574821b28aefb585a4a135e41dd7">1973</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa9ef574821b28aefb585a4a135e41dd7">EmojiEntityMapper::~EmojiEntityMapper</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### name() {#a33137ef11c5d63f6f7d7a27c01db943e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * EmojiEntityMapper::name (int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Access routine to the name of the Emoji entity.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">index</td>
<td class="doxyParamItemDescription">code of the requested Emoji entity returned by <a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index()</a></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
the name of the Emoji entity in GitHub format (i.e. :smile:)
</dd>
</dl>


Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 2026 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33137ef11c5d63f6f7d7a27c01db943e">2026</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index&gt;=0 &amp;&amp; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(index)&lt;<a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a> ? <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>[index].<a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a> : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g\_emojiEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g\_numEmojiEntities</a> and <a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a>.

Referenced by <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a>, <a href="#a33137ef11c5d63f6f7d7a27c01db943e">name</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae151cc7686cf768f2e7e91002bac8dcc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a69768613d52a739ff1824beee29e9c52">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8b0c3df81502ad08c0887a26b78061c2">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a>.
</div>
</div>

### symbol2index() {#a8f20a25544d61a753eaf73d2618c9c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int EmojiEntityMapper::symbol2index (const std::string &amp; symName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns a code for the requested Emoji entity name.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symName</td>
<td class="doxyParamItemDescription">Emoji entity name</td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
the code for the requested Emoji entity name, in case the requested Emoji item does not exist <span class="doxyComputerOutput">-1</span> is returned.
</dd>
</dl>


Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 1990 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f20a25544d61a753eaf73d2618c9c88">1990</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8f20a25544d61a753eaf73d2618c9c88">EmojiEntityMapper::symbol2index</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;symName)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a>.find(symName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a>.end() ? it-&gt;second : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m\_name2symGh</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a> and <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a>.
</div>
</div>

### unicode() {#a1b6d7e3d1f82adf44c46fdd82d11b2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * EmojiEntityMapper::unicode (int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Access routine to the unicode sequence for the Emoji entity.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">index</td>
<td class="doxyParamItemDescription">code of the requested Emoji entity returned by <a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index()</a></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
the unicode sequence of the Emoji entity,
</dd>
</dl>


Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 2016 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">2016</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index&gt;=0 &amp;&amp; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(index)&lt;<a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a> ? <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>[index].<a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a> : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g\_emojiEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g\_numEmojiEntities</a> and <a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0eca51c43b643d592b22070d062a3b77">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa066a9ae73449ff8017a1e94565fae2e">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a23c1a244d091ae31fcd8ff2d66747054">TextDocVisitor::operator()</a> and <a href="#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a>.
</div>
</div>

### writeEmojiFile() {#aa3a564160bf157ebe6a13531392bb48b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmojiEntityMapper::writeEmojiFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Writes the list of supported emojis to the given file.

Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 1999 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3a564160bf157ebe6a13531392bb48b">1999</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa3a564160bf157ebe6a13531392bb48b">EmojiEntityMapper::writeEmojiFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a>; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>[i].name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a6296d06ea0d5be85d060dac04b76d4f7">g_numEmojiCompatibilityEntities</a>; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>[i].oldName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a872534923eff1e9e95b0816e9f2a30b7">g\_emojiCompatibilityEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a8b86138452dd158fe6335f581a491596">g\_emojiEntities</a>, <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#a6296d06ea0d5be85d060dac04b76d4f7">g\_numEmojiCompatibilityEntities</a> and <a href="/web-doxygen/docs/api/files/src/emoji-cpp/#ad516913e9bf2ae76d996ab575a437b97">g\_numEmojiEntities</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_name2symGh {#a5238f2051fdd36ef89e3b009f407f7c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string,int&gt; EmojiEntityMapper::m_name2symGh</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5238f2051fdd36ef89e3b009f407f7c7">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::map&lt;std::</span><span class="doxyHighlightKeywordType">string</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">&gt; <a href="#a5238f2051fdd36ef89e3b009f407f7c7">m_name2symGh</a>;</span></span></div>

</div>


Referenced by <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a> and <a href="#a8f20a25544d61a753eaf73d2618c9c88">symbol2index</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a6b4ebc91738fb8f8af7459346a86f49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmojiEntityMapper &amp; EmojiEntityMapper::instance ()</td>
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

Returns the one and only instance of the Emoji entity mapper.

Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>, definition at line 1978 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b4ebc91738fb8f8af7459346a86f49b">1978</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a> &amp;<a href="#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a> inst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> inst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0eca51c43b643d592b22070d062a3b77">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa066a9ae73449ff8017a1e94565fae2e">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae151cc7686cf768f2e7e91002bac8dcc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a69768613d52a739ff1824beee29e9c52">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8b0c3df81502ad08c0887a26b78061c2">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a23c1a244d091ae31fcd8ff2d66747054">TextDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### s\_instance {#aefd0bd31e345895d4f8fd2d864e3d3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmojiEntityMapper * EmojiEntityMapper::s_instance = nullptr</td>
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



Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefd0bd31e345895d4f8fd2d864e3d3d5">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    static <a href="#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper</a> *<a href="#aefd0bd31e345895d4f8fd2d864e3d3d5">s_instance</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
