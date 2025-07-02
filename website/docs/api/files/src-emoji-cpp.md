---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/emoji-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `emoji.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/emojientityinfo">emojiEntityInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/emojientitycompatibility">emojiEntityCompatibility</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a> = sizeof(<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>)/sizeof(*<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6296d06ea0d5be85d060dac04b76d4f7">g_numEmojiCompatibilityEntities</a> = sizeof(<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>)/sizeof(*<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>)</td>
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

## Variables

### g\_emojiCompatibilityEntities {#a872534923eff1e9e95b0816e9f2a30b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct emojiEntityCompatibility g_emojiCompatibilityEntities[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
{
  {":blonde_man:",                            ":blond_haired_man:"},
  {":person_frowning:",                       ":frowning_person:"},
  {":person_with_blond_hair:",                ":blond_haired_person:"},
  {":person_with_pouting_face:",              ":pouting_face:"},
}
</div>
</dd>
</dl>

Definition at line 1953 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper::EmojiEntityMapper</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa3a564160bf157ebe6a13531392bb48b">EmojiEntityMapper::writeEmojiFile</a>.
</div>
</div>

### g\_emojiEntities {#a8b86138452dd158fe6335f581a491596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct emojiEntityInfo g_emojiEntities[]</td>
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



Definition at line 1941 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper::EmojiEntityMapper</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa3a564160bf157ebe6a13531392bb48b">EmojiEntityMapper::writeEmojiFile</a>.
</div>
</div>

### g\_numEmojiCompatibilityEntities {#a6296d06ea0d5be85d060dac04b76d4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t g_numEmojiCompatibilityEntities = sizeof(<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>)/sizeof(*<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>)</td>
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



Definition at line 1956 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6296d06ea0d5be85d060dac04b76d4f7">1956</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a6296d06ea0d5be85d060dac04b76d4f7">g_numEmojiCompatibilityEntities</a> = </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>)/</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(*<a href="#a872534923eff1e9e95b0816e9f2a30b7">g_emojiCompatibilityEntities</a>);</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper::EmojiEntityMapper</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa3a564160bf157ebe6a13531392bb48b">EmojiEntityMapper::writeEmojiFile</a>.
</div>
</div>

### g\_numEmojiEntities {#ad516913e9bf2ae76d996ab575a437b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t g_numEmojiEntities = sizeof(<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>)/sizeof(*<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>)</td>
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



Definition at line 1955 of file <a href="/web-doxygen/docs/api/files/src/emoji-cpp">emoji.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad516913e9bf2ae76d996ab575a437b97">1955</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ad516913e9bf2ae76d996ab575a437b97">g_numEmojiEntities</a> = </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>)/</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(*<a href="#a8b86138452dd158fe6335f581a491596">g_emojiEntities</a>);</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa0e24fab34771f5263da10a2fc3c593e">EmojiEntityMapper::EmojiEntityMapper</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#aa3a564160bf157ebe6a13531392bb48b">EmojiEntityMapper::writeEmojiFile</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
