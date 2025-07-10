---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/vhdldocgen-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `vhdldocgen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;string.h&gt;
#include &lt;map&gt;
#include &lt;algorithm&gt;
#include &lt;unordered_set&gt;
#include &lt;mutex&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c0d52cf3683a329ebcc7417519b310">initUCF</a> (Entry *root, const QCString &amp;type, QCString &amp;qcs, int line, const QCString &amp;fileName, QCString &amp;brief)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a> (const MemberDef *mdef, OutputList &amp;ol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab534a27eef617922af2a5d7baafffcae">addInstance</a> (ClassDefMutable *entity, ClassDefMutable *arch, ClassDefMutable *inst, const std::shared_ptr&lt; Entry &gt; &amp;cur)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e22c140f692291551eb95a7e1867b8f">writeLink</a> (const MemberDef *mdef, OutputList &amp;ol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a> (const QCString &amp;q, const char *keyword, OutputList &amp;ol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e22ceaa05ae493f2f3892681aec351">splitString</a> (QCString &amp;str, char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac853f7c85a98e5ef7040604706c7b80c">compareString</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a> (const MemberList *ml, VhdlSpecifier type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180fa3a09e24b54ffad20ec6bcef86da">findMemFlow</a> (const MemberDef *mdef)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3bead6f8cce482f4db02c92a770ab5">alignText</a> (QCString &amp;q)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a> =nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const std::unordered_set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35879b543355733a32a4f8f31c84015b">g_vhdlKeyWordSet0</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const std::unordered_set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc785c02b3f5126f0cf9a9365fd5539d">g_vhdlKeyWordSet1</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const std::unordered_set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bbf68b43e28bc0d97f5eaa113dba61">g_vhdlKeyWordSet2</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const std::unordered_set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d25df0469c1e88bd16bcae72325430">g_vhdlKeyWordSet3</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::recursive_mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::map&lt; std::string, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15003ec22aceea0954f320c3092588b1">g_classList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::map&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *, std::vector&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d899e3d331a47d8c765340997d0207">recordCounter</a> =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab79d2d52d43f3c22214135a989f88d">mdList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2683e87d60a00e06c996a17faabf7c6">ifcounter</a> =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c86cd9f03e0a8ffb5c6676325ca2d20">nodeCounter</a> =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b53ed9446260849c8a200b362c97c37">textNodeLink</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685fd32cd6b22bb9302c2d456c1ba6cb">yesNodeLink</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fcc4cce611bc4cce6539a7b821efc1">noNodeLink</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3490b21727b2da346e15ed4fb8937b">decisionNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c24e80a4e2efc78c082b446e1a13a2">varNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae261a70614d30ab993e7db91ab7f6c6a">startEndNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44294ad1ec4e31fd82000879621d53c">textNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5a61a47a4a9b1a6004c718ed9e6495">flowCol</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/flowchart">FlowChart</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b3784e26a172c464443fb55a30364d">flowList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVhdlType</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd32ac165b45cf0bd6eb6aeb189c98fe">STARTL</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab1f2b37b1283016df2dee1690c4846">DECLN</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe49c281c00844e55c25aacf8b4ee1a2">STARTFIN</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca1d1feec1c0b7fc94f2de8265155467ec">FlowChart::START_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572cacd28dbdea10a3dc04788bb5b7f93237a">FlowChart::END_NO</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8f11caf539de9555d07b4e7ef5b1da">LOOP</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547a0048650bcde0b41268c7bbdabaf9">ENDCL</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca8b7e33a5f0231ba2cb96929a1bb3ec59">FlowChart::END_CASE</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca7596c90f02f7c88a6322c09b60ee76a1">FlowChart::END_LOOP</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ed36e089ae23fbd0742efe34acf322">EEND</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca179994ac1a96f9177e2bb34d949c16a4">FlowChart::ENDIF_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca23ef4fff80ce6ee01198e2eed1d74ec2">FlowChart::ELSE_NO</a> )</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2683dde5ae950c9c69ec580cff66f359">IFF</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca016ebee2535fd749ec83e830c93dae86">FlowChart::IF_NO</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb52f0bd95d6390d6fc0943d1c3f638f">EXITNEXT</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca816c3e602bf735d34804cdbd1f32adf0">FlowChart::EXIT_NO</a>      | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca34ecdc72ac6ea03993ca144ae7708be6">FlowChart::NEXT_NO</a> )</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7cf2a3641be7b89138615764d60ba3">EMPTY</a>&nbsp;&nbsp;&nbsp;(<a href="#ad5ed36e089ae23fbd0742efe34acf322">EEND</a>                    | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40069882b1f09d9463acc3acd7b67708">EE</a>&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca23ef4fff80ce6ee01198e2eed1d74ec2">FlowChart::ELSE_NO</a>      | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1d82fd8ca87949d08fe77d7562d978">EMPTNODE</a>&nbsp;&nbsp;&nbsp;(<a href="#a547a0048650bcde0b41268c7bbdabaf9">ENDCL</a> | <a href="#ad5ed36e089ae23fbd0742efe34acf322">EEND</a>            | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202add8ca5d891a736b7865fd7bc733f">FLOWLEN</a>&nbsp;&nbsp;&nbsp;(flowList.size()-1)</td>
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

### addInstance() {#ab534a27eef617922af2a5d7baafffcae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addInstance (<a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> * entity, <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> * arch, <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> * inst, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; cur)</td>
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



<p>Definition at line 2191 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab534a27eef617922af2a5d7baafffcae">2191</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab534a27eef617922af2a5d7baafffcae">addInstance</a>(<a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a>* classEntity, <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a>* ar,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *cd , </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;cur)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bName,n1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ar==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (classEntity==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//add component inst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">    n1=cur-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> ferr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (classEntity==cd) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  bName=classEntity-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// fprintf(stderr,"\naddInstance %s to %s %s %s\n",qPrint( classEntity-&gt;name()),qPrint(cd-&gt;name()),qPrint(ar-&gt;name()),cur-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">  n1=classEntity-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">isBaseClass</a>(classEntity, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">    cd-&gt;<a href="/web-doxygen/docs/api/classes/classdefmutable/#a761d9f7cc2f81e4ac4211e265540bace">insertBaseClass</a>(classEntity,n1,Protection::Public,Specifier::Normal,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>(cd,classEntity);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>(classEntity,cd,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">    classEntity-&gt;<a href="/web-doxygen/docs/api/classes/classdefmutable/#a9455d0a7225968447a4bb2b7ce6eb46c">insertSubClass</a>(cd,Protection::Public,Specifier::Normal,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">    classEntity-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#aa0c1e834027250c7b3bcffcd73e96c3d">setLanguage</a>(SrcLangExt::VHDL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">ferr:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> uu=cur-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#afc503b94aed5230ca07d22e743e9c800">createMemberDef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">      ar-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(), cur-&gt;startLine,cur-&gt;startColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">      n1,uu,uu, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">      Protection::Public,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">      Specifier::Normal,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">      cur-&gt;isStatic,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">      Relationship::Member,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mmd = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(md.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ar-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/taginfo">TagInfo</a> tg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">    tg.<a href="/web-doxygen/docs/api/structs/taginfo/#a1cc95c706df919ed12443c7574e12aa0">anchor</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">    tg.<a href="/web-doxygen/docs/api/structs/taginfo/#a7c046d5ccf0095527213dabbbf0949f9">fileName</a> = ar-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">    tg.<a href="/web-doxygen/docs/api/structs/taginfo/#a8f42f0aff3cb6df860f7b5ba27f6cd2f">tagName</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">    mmd-&gt;setTagInfo(&amp;tg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//fprintf(stderr,"\n%s%s%s\n",qPrint(md-&gt;name()),qPrint(cur-&gt;brief),qPrint(cur-&gt;doc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;setLanguage(SrcLangExt::VHDL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;setVhdlSpecifiers(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;setBriefDescription(cur-&gt;brief,cur-&gt;briefFile,cur-&gt;briefLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;setBodySegment(cur-&gt;startLine,cur-&gt;startLine,-1) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;setDocumentation(cur-&gt;doc,cur-&gt;docFile,cur-&gt;docLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd=ar-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">  mmd-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">setBodyDef</a>(fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">  ar-&gt;<a href="/web-doxygen/docs/api/classes/classdefmutable/#aceb3bff3f6febf20e1abb61386da66e7">insertMember</a>(md.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/membername">MemberName</a> *mn = <a href="/web-doxygen/docs/api/classes/doxygen/#a6c68c48d8e3dac65c86b39ab838a5f9e">Doxygen::functionNameLinkedMap</a>-&gt;add(uu);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">  mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#af5b01c0bc171ba35e0bc2a33d9c88563">push_back</a>(std::move(md));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/structs/taginfo/#a1cc95c706df919ed12443c7574e12aa0">TagInfo::anchor</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#afc503b94aed5230ca07d22e743e9c800">createMemberDef</a>, <a href="/web-doxygen/docs/api/structs/taginfo/#a7c046d5ccf0095527213dabbbf0949f9">TagInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6c68c48d8e3dac65c86b39ab838a5f9e">Doxygen::functionNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">ClassDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#a761d9f7cc2f81e4ac4211e265540bace">ClassDefMutable::insertBaseClass</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#aceb3bff3f6febf20e1abb61386da66e7">ClassDefMutable::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#a9455d0a7225968447a4bb2b7ce6eb46c">ClassDefMutable::insertSubClass</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">ClassDef::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/membername/#af5b01c0bc171ba35e0bc2a33d9c88563">MemberName::push_back</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">DefinitionMutable::setBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#aa0c1e834027250c7b3bcffcd73e96c3d">DefinitionMutable::setLanguage</a>, <a href="/web-doxygen/docs/api/structs/taginfo/#a8f42f0aff3cb6df860f7b5ba27f6cd2f">TagInfo::tagName</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab8681769cd2f027fbf46a4836d3825e9">VhdlDocGen::computeVhdlComponentRelations</a>.</p>

</div>
</div>

### alignText() {#abc3bead6f8cce482f4db02c92a770ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void alignText (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2553 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc3bead6f8cce482f4db02c92a770ab5">2553</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (q.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&lt;=80) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (q.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;200)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">    q.<a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">resize</a>(200);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">  q.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">" ..."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> str(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;80)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2569</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j=std::max(str.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,80),str.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">,80));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">      q=temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs=str.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=qcs+</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=</span><span class="doxyHighlightStringLiteral">"n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">      str.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">//while</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight"> q=temp+str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlightComment">// #endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">QCString::resize</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### compareString() {#ac853f7c85a98e5ef7040604706c7b80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int compareString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac853f7c85a98e5ef7040604706c7b80c">117</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac853f7c85a98e5ef7040604706c7b80c">compareString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; s1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; s2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>(),s2.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a765683cbd1cf5a8e7374b64a9ac37d98">VhdlDocGen::findFunction</a>.</p>

</div>
</div>

### findMemFlow() {#a180fa3a09e24b54ffad20ec6bcef86da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * findMemFlow (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



<p>Definition at line 2390 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a180fa3a09e24b54ffad20ec6bcef86da">2390</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* <a href="#a180fa3a09e24b54ffad20ec6bcef86da">findMemFlow</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : <a href="#a3ab79d2d52d43f3c22214135a989f88d">mdList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;name()==mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() &amp;&amp;  md-&gt;getStartBodyLine()==mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="#a3ab79d2d52d43f3c22214135a989f88d">mdList</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a>.</p>

</div>
</div>

### getSpecifierTypeFromClass() {#ab51377e0618f4b5bc839c21db9339571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlSpecifier getSpecifierTypeFromClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



<p>Definition at line 414 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab51377e0618f4b5bc839c21db9339571">414</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> <a href="#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0">VhdlDocGen::VhdlClasses</a> ii=<a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">VhdlSpecifier::ENTITY</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">VhdlSpecifier::ARCHITECTURE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">VhdlSpecifier::PACKAGE_BODY</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">VhdlDocGen::PACKAGECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">VhdlSpecifier::PACKAGE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">VhdlSpecifier::UNKNOWN</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">ARCHITECTURE</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">ENTITY</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">PACKAGE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">PACKAGE_BODY</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">VhdlDocGen::PACKAGECLASS</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad5d4c791af3f2943467c7c7af558d83a">VhdlDocGen::getClassTitle</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>.</p>

</div>
</div>

### initUCF() {#a17c0d52cf3683a329ebcc7417519b310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initUCF (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; qcs, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; brief)</td>
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



<p>Definition at line 1977 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17c0d52cf3683a329ebcc7417519b310">1977</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a>* root,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;qcs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(qcs,</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> <a href="/web-doxygen/docs/api/namespaces/reg">reg</a>(R</span><span class="doxyHighlightStringLiteral">"([\s=])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="/web-doxygen/docs/api/namespaces/reg">reg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">    n=type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(n,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">    n=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  qcs.prepend("|");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; current = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;vhdlSpec=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;section=EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;bodyLine=line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;fileName=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;type=</span><span class="doxyHighlightStringLiteral">"ucf_const"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;args+=qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;lang=  SrcLangExt::VHDL ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// adding dummy name for constraints like VOLTAGE=5,TEMPERATURE=20 C</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    n=</span><span class="doxyHighlightStringLiteral">"dummy"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    n+=<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;name= n+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  current-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!brief.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">    current-&gt;brief=brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">    current-&gt;briefLine=line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">    current-&gt;briefFile=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">    brief.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a07c79aba42cd96fbf689c324e4e31da7">moveToSubEntryAndKeep</a>(current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/entry/#a07c79aba42cd96fbf689c324e4e31da7">Entry::moveToSubEntryAndKeep</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">UCF_CONST</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>.</p>

</div>
</div>

### membersHaveSpecificType() {#a9b31309c5cf2471cbe9622a64f969473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool membersHaveSpecificType (const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> type)</td>
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



<p>Definition at line 1725 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b31309c5cf2471cbe9622a64f969473">1725</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mdd : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdd-&gt;getVhdlSpecifiers()==type) </span><span class="doxyHighlightComment">//is type in class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#af6d805d822b673a443308b6363d9c85f">getMemberGroupList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mg-&gt;members().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>(&amp;mg-&gt;members(),type)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af6d805d822b673a443308b6363d9c85f">MemberList::getMemberGroupList</a>, <a href="#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.</p>

</div>
</div>

### splitString() {#a67e22ceaa05ae493f2f3892681aec351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString splitString (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, char c)</td>
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



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67e22ceaa05ae493f2f3892681aec351">105</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a67e22ceaa05ae493f2f3892681aec351">splitString</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; str,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=str.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    n=str.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    str=str.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>.</p>


<p>Referenced by <a href="#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>.</p>

</div>
</div>

### startFonts() {#a443391a41c8ca5dd93aa555beeb1955d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startFonts (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; q, const char * keyword, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a443391a41c8ca5dd93aa555beeb1955d">97</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; q, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *keyword,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;codeOL = ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a284458e4baf27869eb5bbb9776407e6c">codeGenerators</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  codeOL.<a href="/web-doxygen/docs/api/classes/outputcodelist/#ad5f1dacf0a9323f4471c33f81c1319d9">startFontClass</a>(keyword);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  codeOL.codify(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  codeOL.endFontClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputlist/#a284458e4baf27869eb5bbb9776407e6c">OutputList::codeGenerators</a> and <a href="/web-doxygen/docs/api/classes/outputcodelist/#ad5f1dacf0a9323f4471c33f81c1319d9">OutputCodeList::startFontClass</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>.</p>

</div>
</div>

### writeLink() {#a5e22c140f692291551eb95a7e1867b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeLink (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e22c140f692291551eb95a7e1867b8f">89</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>, <a href="#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.</p>

</div>
</div>

### writeUCFLink() {#a1f76f36afd77f874d16385ffbe83e1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeUCFLink (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



<p>Definition at line 2034 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f76f36afd77f874d16385ffbe83e1c8">2034</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n= <a href="#a67e22ceaa05ae493f2f3892681aec351">splitString</a>(largs, </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// VhdlDocGen::adjustRecordMember(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> equ=(n.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()==largs.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!equ)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightStringLiteral">"dummy"</span><span class="doxyHighlight">)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (equ)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a67e22ceaa05ae493f2f3892681aec351">splitString</a>, <a href="#a5e22c140f692291551eb95a7e1867b8f">writeLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">OutputList::writeString</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### comment {#ae8c2c4e6dab650ca0dbc32956838ddd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* comment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2531 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8c2c4e6dab650ca0dbc32956838ddd9">2531</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5a47760391ae7b0e270bd1de323be1e0">codifyLines</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.</p>

</div>
</div>

### decisionNode {#a4c3490b21727b2da346e15ed4fb8937b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* decisionNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2532 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c3490b21727b2da346e15ed4fb8937b">2532</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#a4c3490b21727b2da346e15ed4fb8937b">decisionNode</a>;</span></span></div>

</div>

</div>
</div>

### flowCol {#a5e5a61a47a4a9b1a6004c718ed9e6495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct  flowCol</td>
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
{ "green",       
  "red",         
  "black",       
  "khaki",       
  "0.7 0.3 1.0", 
  "lightyellow", 
  "white",       
  "lightcyan"    
}
</div>
</dd>
</dl>

<p>Definition at line 2545 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#abe5bc298b8ac3b911af947e2b29089f5">FlowChart::buildCommentNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a20d4f7b89091aeb52c0349fd9e553409">FlowChart::writeEdge</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### flowList {#a58b3784e26a172c464443fb55a30364d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FlowChart&gt; flowList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2547 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a58b3784e26a172c464443fb55a30364d">2547</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::vector&lt;FlowChart&gt; <a href="#a58b3784e26a172c464443fb55a30364d">flowList</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#abe5bc298b8ac3b911af947e2b29089f5">FlowChart::buildCommentNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a64f98636bae1290688ea4bc06d02e86f">FlowChart::delFlowList</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a590a484692d935d4850c7e6bce508d01">FlowChart::findLabel</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a82fc425100d1cf68c08bad05195bf2f3">FlowChart::findNextLoop</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aba76e82b248e1113568acd458e2b7b21">FlowChart::findNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a0305aa29048ee638ab09b4dc4bf28a9f">FlowChart::findPrevLoop</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a948abd6948d3e24f3e9dec7eff2c3a18">FlowChart::getNextIfLink</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a660d99edcee9c4dd556b42b8aa1dd4da">FlowChart::getNextNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a25647e6b336425f3f5ccef2ecea0dcf1">FlowChart::printFlowTree</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a66989e6892ad6bbb539241dedbfc4f9e">FlowChart::writeFlowChart</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a>.</p>

</div>
</div>

### flowMember {#a564ccf36eb7cf220de5f5252a9a2b0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef* flowMember =nullptr</td>
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



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a564ccf36eb7cf220de5f5252a9a2b0da">75</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a7808cdf56c299daceed3212b65b8a031">VhdlDocGen::setFlowMember</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae7d4d0c22eac6e04a900b847c702a157">VhdlDocGen::writeRecordProto</a>.</p>

</div>
</div>

### g\_classList {#a15003ec22aceea0954f320c3092588b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ClassDef*&gt; g_classList</td>
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



<p>Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15003ec22aceea0954f320c3092588b1">214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::vector&lt;ClassDef*&gt;                      <a href="#a15003ec22aceea0954f320c3092588b1">g_classList</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a60e16e249eaf1829c224b054ff743ce7">VhdlDocGen::resetCodeVhdlParserState</a>.</p>

</div>
</div>

### g\_packages {#a4f0ee2fc6fdee2414cb783cb977becd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ClassDef*,std::vector&lt;ClassDef*&gt; &gt; g_packages</td>
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



<p>Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f0ee2fc6fdee2414cb783cb977becd7">215</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::map&lt;ClassDef*,std::vector&lt;ClassDef*&gt; &gt; <a href="#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a60e16e249eaf1829c224b054ff743ce7">VhdlDocGen::resetCodeVhdlParserState</a>.</p>

</div>
</div>

### g\_varMap {#a3cc5f535e1a84284407b715e1b40f93e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string,const MemberDef*&gt; g_varMap</td>
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



<p>Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3cc5f535e1a84284407b715e1b40f93e">213</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::map&lt;std::string,const MemberDef*&gt;      <a href="#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a60e16e249eaf1829c224b054ff743ce7">VhdlDocGen::resetCodeVhdlParserState</a>.</p>

</div>
</div>

### g\_vhdlKeyWordSet0 {#a35879b543355733a32a4f8f31c84015b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unordered_set&lt; std::string &gt; g_vhdlKeyWordSet0</td>
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
  "abs","access","after","alias","all","and","architecture","array","assert","assume","assume_guarantee","attribute",
  "begin","block","body","buffer","bus",
  "case","component","configuration","constant","context","cover",
  "default","disconnect","downto",
  "else","elsif","end","entity","exit",
  "fairness","file","for","force","function",
  "generate","generic","group","guarded",
  "if","impure","in","inertial","inout","is",
  "label","library","linkage","literal","loop",
  "map","mod",
  "nand","new","next","nor","not","null",
  "of","on","open","or","others","out",
  "package","parameter","port","postponed","procedure","process","property","protected","pure",
  "range","record","register","reject","release","restrict","restrict_guarantee","rem","report","rol","ror","return",
  "select","sequence","severity","signal","shared","sla","sll","sra","srl","strong","subtype",
  "then","to","transport","type",
  "unaffected","units","until","use",
  "variable","vmode","vprop","vunit",
  "wait","when","while","with",
  "xor","xnor"
}
</div>
</dd>
</dl>

<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35879b543355733a32a4f8f31c84015b">125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_set&lt; std::string &gt; <a href="#a35879b543355733a32a4f8f31c84015b">g_vhdlKeyWordSet0</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"abs"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"access"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"after"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"alias"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"all"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"and"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"architecture"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"array"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"assert"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"assume"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"assume_guarantee"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"attribute"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"begin"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"block"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"body"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"buffer"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"bus"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"case"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"component"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"configuration"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"constant"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"context"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"cover"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"default"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"disconnect"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"downto"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"else"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"elsif"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"entity"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"exit"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"fairness"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"for"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"force"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"generate"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"group"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"guarded"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"if"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"impure"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"inertial"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"inout"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"is"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"label"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"library"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"linkage"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"literal"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"loop"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"map"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"mod"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"nand"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"new"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"next"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"nor"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"not"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"null"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"of"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"on"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"open"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"or"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"others"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"out"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"parameter"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"port"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"postponed"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"procedure"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"process"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"protected"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"pure"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"range"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"record"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"register"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"reject"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"release"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"restrict"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"restrict_guarantee"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"rem"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"report"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"rol"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"ror"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"return"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"select"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"severity"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"shared"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sla"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sll"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sra"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"srl"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"strong"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"subtype"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"then"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"to"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"transport"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"unaffected"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"units"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"until"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"use"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"variable"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"vmode"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"vprop"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"vunit"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"wait"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"when"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"while"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"with"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"xor"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"xnor"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>.</p>

</div>
</div>

### g\_vhdlKeyWordSet1 {#afc785c02b3f5126f0cf9a9365fd5539d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unordered_set&lt; std::string&gt; g_vhdlKeyWordSet1</td>
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
  "natural","unsigned","signed","string","boolean", "bit","bit_vector","character",
  "std_ulogic","std_ulogic_vector","std_logic","std_logic_vector","integer",
  "real","float","ufixed","sfixed","time","positive"
}
</div>
</dd>
</dl>

<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc785c02b3f5126f0cf9a9365fd5539d">151</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_set&lt; std::string&gt; <a href="#afc785c02b3f5126f0cf9a9365fd5539d">g_vhdlKeyWordSet1</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"natural"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"unsigned"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"signed"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"string"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"boolean"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"bit"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"bit_vector"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"character"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"std_ulogic"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"std_ulogic_vector"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"std_logic"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"std_logic_vector"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"integer"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"real"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"float"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"ufixed"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sfixed"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"time"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"positive"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>.</p>

</div>
</div>

### g\_vhdlKeyWordSet2 {#aa5bbf68b43e28bc0d97f5eaa113dba61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unordered_set&lt; std::string &gt; g_vhdlKeyWordSet2</td>
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
  "abs","and","or","not","mod","xor","rem","xnor","ror","rol","sla","sll"
}
</div>
</dd>
</dl>

<p>Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5bbf68b43e28bc0d97f5eaa113dba61">159</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_set&lt; std::string &gt; <a href="#aa5bbf68b43e28bc0d97f5eaa113dba61">g_vhdlKeyWordSet2</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"abs"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"and"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"or"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"not"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"mod"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"xor"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"rem"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"xnor"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"ror"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"rol"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sla"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"sll"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>.</p>

</div>
</div>

### g\_vhdlKeyWordSet3 {#ad1d25df0469c1e88bd16bcae72325430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unordered_set&lt; std::string &gt; g_vhdlKeyWordSet3</td>
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
  "base","left","right","high","low","ascending",
  "image","value","pos","val","succ","pred","leftof","rightof","left","right","high","low",
  "range","reverse_range","length","ascending","delayed","stable","quiet","transaction","event",
  "active","last_event","last_active","last_value","driving","driving_value","simple_name","instance_name","path_name"
}
</div>
</dd>
</dl>

<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1d25df0469c1e88bd16bcae72325430">165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_set&lt; std::string &gt; <a href="#ad1d25df0469c1e88bd16bcae72325430">g_vhdlKeyWordSet3</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"base"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"left"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"right"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"high"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"low"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"ascending"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"image"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"pos"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"val"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"succ"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"pred"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"leftof"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"rightof"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"left"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"right"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"high"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"low"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"range"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"reverse_range"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"length"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"ascending"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"delayed"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"stable"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"quiet"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"transaction"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"event"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"active"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"last_event"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"last_active"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"last_value"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"driving"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"driving_value"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"simple_name"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"instance_name"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"path_name"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>.</p>

</div>
</div>

### g\_vhdlMutex {#aee6adbe29081b799cea6fc0a906df2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex g_vhdlMutex</td>
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



<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee6adbe29081b799cea6fc0a906df2f1">212</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::recursive_mutex                        <a href="#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a60e16e249eaf1829c224b054ff743ce7">VhdlDocGen::resetCodeVhdlParserState</a>.</p>

</div>
</div>

### ifcounter {#ab2683e87d60a00e06c996a17faabf7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ifcounter =0</td>
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



<p>Definition at line 2520 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2683e87d60a00e06c996a17faabf7c6">2520</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ab2683e87d60a00e06c996a17faabf7c6">ifcounter</a>=0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a64f98636bae1290688ea4bc06d02e86f">FlowChart::delFlowList</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ad62b02a6d1de25c45eb027c0238f7075">FlowChart::FlowChart</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a9ddf7f6aff23849c4bbb90afbabd38c1">FlowChart::moveToPrevLevel</a>.</p>

</div>
</div>

### mdList {#a3ab79d2d52d43f3c22214135a989f88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const MemberDef*&gt; mdList</td>
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



<p>Definition at line 2388 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ab79d2d52d43f3c22214135a989f88d">2388</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::vector&lt;const MemberDef*&gt; <a href="#a3ab79d2d52d43f3c22214135a989f88d">mdList</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a> and <a href="#a180fa3a09e24b54ffad20ec6bcef86da">findMemFlow</a>.</p>

</div>
</div>

### nodeCounter {#a3c86cd9f03e0a8ffb5c6676325ca2d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int nodeCounter =0</td>
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



<p>Definition at line 2521 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c86cd9f03e0a8ffb5c6676325ca2d20">2521</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3c86cd9f03e0a8ffb5c6676325ca2d20">nodeCounter</a>=0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a64f98636bae1290688ea4bc06d02e86f">FlowChart::delFlowList</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#ad62b02a6d1de25c45eb027c0238f7075">FlowChart::FlowChart</a>.</p>

</div>
</div>

### noNodeLink {#a19fcc4cce611bc4cce6539a7b821efc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* noNodeLink</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2528 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19fcc4cce611bc4cce6539a7b821efc1">2528</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a19fcc4cce611bc4cce6539a7b821efc1">noNodeLink</a>;</span></span></div>

</div>

</div>
</div>

### recordCounter {#a56d899e3d331a47d8c765340997d0207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int recordCounter =0</td>
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



<p>Definition at line 738 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56d899e3d331a47d8c765340997d0207">738</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a56d899e3d331a47d8c765340997d0207">recordCounter</a>=0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>.</p>

</div>
</div>

### startEndNode {#ae261a70614d30ab993e7db91ab7f6c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* startEndNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2534 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae261a70614d30ab993e7db91ab7f6c6a">2534</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ae261a70614d30ab993e7db91ab7f6c6a">startEndNode</a>;</span></span></div>

</div>

</div>
</div>

### textNode {#ac44294ad1ec4e31fd82000879621d53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* textNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2535 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac44294ad1ec4e31fd82000879621d53c">2535</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#ac44294ad1ec4e31fd82000879621d53c">textNode</a>;</span></span></div>

</div>

</div>
</div>

### textNodeLink {#a9b53ed9446260849c8a200b362c97c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* textNodeLink</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2526 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b53ed9446260849c8a200b362c97c37">2526</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9b53ed9446260849c8a200b362c97c37">textNodeLink</a>;</span></span></div>

</div>

</div>
</div>

### varNode {#ab5c24e80a4e2efc78c082b446e1a13a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* varNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2533 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5c24e80a4e2efc78c082b446e1a13a2">2533</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#ab5c24e80a4e2efc78c082b446e1a13a2">varNode</a>;</span></span></div>

</div>

</div>
</div>

### yesNodeLink {#a685fd32cd6b22bb9302c2d456c1ba6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* yesNodeLink</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2527 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a685fd32cd6b22bb9302c2d456c1ba6cb">2527</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a685fd32cd6b22bb9302c2d456c1ba6cb">yesNodeLink</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DECLN {#aaab1f2b37b1283016df2dee1690c4846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLN&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">                  (<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572cadb18b146f68f17a2005af45fd53a41d3">FlowChart::WHEN_NO</a>      | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca016ebee2535fd749ec83e830c93dae86">FlowChart::IF_NO</a>    | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca20ebc89c9bca7b02af08669632b9a658">FlowChart::FOR_NO</a>       | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca83a7f901b277a6663270779a1b4619ed">FlowChart::WHILE_NO</a> | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caddeba7e93199e159a70560537023be3d">FlowChart::CASE_NO</a>      | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca5d1c9a27d84209bf8c7fab031bb52ca4">FlowChart::LOOP_NO</a> )
</div>
</dd>
</dl>

<p>Definition at line 2504 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaab1f2b37b1283016df2dee1690c4846">2504</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DECLN    (FlowChart::WHEN_NO      | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::ELSIF_NO     | FlowChart::IF_NO    | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::FOR_NO       | FlowChart::WHILE_NO | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::CASE_NO      | FlowChart::LOOP_NO )</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### EE {#a40069882b1f09d9463acc3acd7b67708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EE&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca23ef4fff80ce6ee01198e2eed1d74ec2">FlowChart::ELSE_NO</a>      | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2516 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40069882b1f09d9463acc3acd7b67708">2516</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define EE       (FlowChart::ELSE_NO      | FlowChart::ELSIF_NO)</span></span></div>

</div>

</div>
</div>

### EEND {#ad5ed36e089ae23fbd0742efe34acf322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EEND&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca179994ac1a96f9177e2bb34d949c16a4">FlowChart::ENDIF_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca23ef4fff80ce6ee01198e2eed1d74ec2">FlowChart::ELSE_NO</a> )</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2512 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5ed36e089ae23fbd0742efe34acf322">2512</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define EEND     (FlowChart::ENDIF_NO     | FlowChart::ELSE_NO )</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### EMPTNODE {#a8c1d82fd8ca87949d08fe77d7562d978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EMPTNODE&nbsp;&nbsp;&nbsp;(<a href="#a547a0048650bcde0b41268c7bbdabaf9">ENDCL</a> | <a href="#ad5ed36e089ae23fbd0742efe34acf322">EEND</a>            | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2517 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c1d82fd8ca87949d08fe77d7562d978">2517</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define EMPTNODE (ENDCL | EEND            | FlowChart::ELSIF_NO)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>.</p>

</div>
</div>

### EMPTY {#a2b7cf2a3641be7b89138615764d60ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EMPTY&nbsp;&nbsp;&nbsp;(<a href="#ad5ed36e089ae23fbd0742efe34acf322">EEND</a>                    | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2515 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b7cf2a3641be7b89138615764d60ba3">2515</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define EMPTY    (EEND                    | FlowChart::ELSIF_NO)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>.</p>

</div>
</div>

### ENDCL {#a547a0048650bcde0b41268c7bbdabaf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENDCL&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca8b7e33a5f0231ba2cb96929a1bb3ec59">FlowChart::END_CASE</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca7596c90f02f7c88a6322c09b60ee76a1">FlowChart::END_LOOP</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2511 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a547a0048650bcde0b41268c7bbdabaf9">2511</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ENDCL    (FlowChart::END_CASE     | FlowChart::END_LOOP)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### EXITNEXT {#afb52f0bd95d6390d6fc0943d1c3f638f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EXITNEXT&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca816c3e602bf735d34804cdbd1f32adf0">FlowChart::EXIT_NO</a>      | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca34ecdc72ac6ea03993ca144ae7708be6">FlowChart::NEXT_NO</a> )</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2514 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb52f0bd95d6390d6fc0943d1c3f638f">2514</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define EXITNEXT (FlowChart::EXIT_NO      | FlowChart::NEXT_NO )</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### FLOWLEN {#a202add8ca5d891a736b7865fd7bc733f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FLOWLEN&nbsp;&nbsp;&nbsp;(flowList.size()-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2518 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a202add8ca5d891a736b7865fd7bc733f">2518</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define FLOWLEN (flowList.size()-1)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#abe5bc298b8ac3b911af947e2b29089f5">FlowChart::buildCommentNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a660d99edcee9c4dd556b42b8aa1dd4da">FlowChart::getNextNode</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>.</p>

</div>
</div>

### IFF {#a2683dde5ae950c9c69ec580cff66f359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IFF&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caf7a5717aa5bac2f250ab4e68a487912b">FlowChart::ELSIF_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca016ebee2535fd749ec83e830c93dae86">FlowChart::IF_NO</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2513 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2683dde5ae950c9c69ec580cff66f359">2513</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define IFF      (FlowChart::ELSIF_NO     | FlowChart::IF_NO)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### LOOP {#a8e8f11caf539de9555d07b4e7ef5b1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">                  (<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca20ebc89c9bca7b02af08669632b9a658">FlowChart::FOR_NO</a>       | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca83a7f901b277a6663270779a1b4619ed">FlowChart::WHILE_NO</a> | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca5d1c9a27d84209bf8c7fab031bb52ca4">FlowChart::LOOP_NO</a> )
</div>
</dd>
</dl>

<p>Definition at line 2509 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e8f11caf539de9555d07b4e7ef5b1da">2509</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define LOOP     (FlowChart::FOR_NO       | FlowChart::WHILE_NO | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::LOOP_NO )</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a590a484692d935d4850c7e6bce508d01">FlowChart::findLabel</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a0305aa29048ee638ab09b4dc4bf28a9f">FlowChart::findPrevLoop</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### STARTFIN {#abe49c281c00844e55c25aacf8b4ee1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STARTFIN&nbsp;&nbsp;&nbsp;(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca1d1feec1c0b7fc94f2de8265155467ec">FlowChart::START_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572cacd28dbdea10a3dc04788bb5b7f93237a">FlowChart::END_NO</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2508 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe49c281c00844e55c25aacf8b4ee1a2">2508</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define STARTFIN (FlowChart::START_NO     | FlowChart::END_NO)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.</p>

</div>
</div>

### STARTL {#afd32ac165b45cf0bd6eb6aeb189c98fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STARTL&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">                  (<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca83a7f901b277a6663270779a1b4619ed">FlowChart::WHILE_NO</a>     | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca016ebee2535fd749ec83e830c93dae86">FlowChart::IF_NO</a>    | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca20ebc89c9bca7b02af08669632b9a658">FlowChart::FOR_NO</a>       | <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572caddeba7e93199e159a70560537023be3d">FlowChart::CASE_NO</a>  | \
                  <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca5d1c9a27d84209bf8c7fab031bb52ca4">FlowChart::LOOP_NO</a>      | WHEN_NO)
</div>
</dd>
</dl>

<p>Definition at line 2501 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd32ac165b45cf0bd6eb6aeb189c98fe">2501</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define STARTL   (FlowChart::WHILE_NO     | FlowChart::IF_NO    | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::FOR_NO       | FlowChart::CASE_NO  | \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                  FlowChart::LOOP_NO      | WHEN_NO)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#ad62b02a6d1de25c45eb027c0238f7075">FlowChart::FlowChart</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a2885c2afac4a6401e64d765eb44f2d0e">FlowChart::writeEdge</a>.</p>

</div>
</div>

### theTranslator\_vhdlType {#a5c766ca623cbbc0bf6fded310f85f857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define theTranslator_vhdlType&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVhdlType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c766ca623cbbc0bf6fded310f85f857">68</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define theTranslator_vhdlType theTranslator-&gt;trVhdlType</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad5d4c791af3f2943467c7c7af558d83a">VhdlDocGen::getClassTitle</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aa99c6269bf6155f83a12ab796edd4acf">VhdlDocGen::writeVhdlDeclarations</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
