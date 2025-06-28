---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/groupdef-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `groupdef.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;algorithm&gt;
#include &lt;vector&gt;
#include &lt;ctype.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/groupdefimpl">GroupDefImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b23ceba36115840bc62b449edd9a72">createGroupDef</a> (const QCString &amp;fileName, int line, const QCString &amp;name, const QCString &amp;title, const QCString &amp;refFileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a> (const Entry *root, ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a> (const Entry *root, ConceptDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a> (const Entry *root, ModuleDef *mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a> (const Entry *root, NamespaceDef *nd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a> (const Entry *root, DirDef *dd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a> (const Entry *root, GroupDef *subGroup)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a> (const Entry *root, MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a> (const Entry *root, PageDef *eg)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Vec&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a553cf15878cf6e6bdcecf5f8698f4349">groupClassesWithSameScope</a> (Vec &amp;vec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a> (const GroupDef *gd, int level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7300755cb300198b86b98757b2f8311">toGroupDef</a> (const Definition *d)</td>
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

### addClassToGroups() {#a133ed5d7ef56cd0de5d89dcfead564e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addClassToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1444 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a133ed5d7ef56cd0de5d89dcfead564e7">1444</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) gd=<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd &amp;&amp; gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a4a80bd0b7430a7adaf6403f01821becd">addClass</a>(cd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *cdm = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">        cdm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Compound %s: in group %s\n",qPrint(cd-&gt;name()),gd-&gt;groupTitle());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#a4a80bd0b7430a7adaf6403f01821becd">GroupDef::addClass</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>.
</div>
</div>

### addConceptToGroups() {#a9ed7b5fc926a79337a09aa8ecef0e41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addConceptToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1469 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ed7b5fc926a79337a09aa8ecef0e41d">1469</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd &amp;&amp; gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae0e35a187293d00cdccc7da69e3e86a0">addConcept</a>(cd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a> *cdm = <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">        cdm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Compound %s: in group %s\n",qPrint(cd-&gt;name()),gd-&gt;groupTitle());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#ae0e35a187293d00cdccc7da69e3e86a0">GroupDef::addConcept</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>.
</div>
</div>

### addDirToGroups() {#a378ec2ef3e841a44602739461386c1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDirToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1541 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a378ec2ef3e841a44602739461386c1f9">1541</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("*** root-&gt;groups.size()=%d\n",root-&gt;groups.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("group '%s'\n",qPrint(g-&gt;groupname));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">      gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a1cefe14a8b4f2004a76bbcca39e5aada">addDir</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">      dd-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Dir %s: in group %s\n",qPrint(dd-&gt;name()),qPrint(g-&gt;groupname));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#a1cefe14a8b4f2004a76bbcca39e5aada">GroupDef::addDir</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>.
</div>
</div>

### addExampleToGroups() {#af777f735af0317cec08f59bd101c0825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addExampleToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> * eg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1724 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af777f735af0317cec08f59bd101c0825">1724</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> *eg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">      gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a1f7a8ae65f303cde09e95f68d1960e08">addExample</a>(eg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">      eg-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Example %s: in group %s\n",qPrint(eg-&gt;name()),s-&gt;data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#a1f7a8ae65f303cde09e95f68d1960e08">GroupDef::addExample</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.
</div>
</div>

### addGroupToGroups() {#a0b501f4e23a2e8465946abfdfe294c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addGroupToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * subGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1564 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b501f4e23a2e8465946abfdfe294c4c">1564</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *subGroup)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("addGroupToGroups for %s groups=%d\n",qPrint(root-&gt;name),root-&gt;groups.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd==subGroup)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span><span class="doxyHighlightStringLiteral">"Refusing to add group {} to itself"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">            gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (subGroup-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#abbcaaf2e683208c173158a73d512edd0">findGroup</a>(gd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span><span class="doxyHighlightStringLiteral">"Refusing to add group {} to group {}, since the latter is already a "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightStringLiteral">"subgroup of the former"</span><span class="doxyHighlight">, subGroup-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#abbcaaf2e683208c173158a73d512edd0">findGroup</a>(subGroup))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">        gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#aa5e0a4e1a5c815563de6e3ea235da420">addGroup</a>(subGroup);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">        subGroup-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#aa5e0a4e1a5c815563de6e3ea235da420">GroupDef::addGroup</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#abbcaaf2e683208c173158a73d512edd0">GroupDef::findGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2907cfb329df93257c355ceaa29993d7">organizeSubGroupsFiltered</a>.
</div>
</div>

### addMemberToGroups() {#affd271e102af38c14812ccc21a86401c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addMemberToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Add a member to the group with the highest priority</p>

<p>Definition at line 1599 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affd271e102af38c14812ccc21a86401c">1599</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("addMemberToGroups:  Root %p = %s, md %p=%s groups=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    root, qPrint(root-&gt;name), md, qPrint(md-&gt;name()), root-&gt;groups.size() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Search entry's group list for group with highest pri.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70">Grouping::GroupPri_t</a> pri = <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b">Grouping::GROUPING_LOWEST</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *fgd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) gd=<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> &gt;= pri)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fgd &amp;&amp; gd!=fgd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a>==pri)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"Member {} found in multiple {} groups! "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"The member will be put in group {}, and not in group {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">            md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( pri ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">            gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), fgd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">      fgd = gd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">      pri = g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("fgd=%p\n",fgd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// put member into group defined by this entry?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fgd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *mgd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("mgd=%p\n",mgd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insertit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mgd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">      insertit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mgd!=fgd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> moveit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// move member from one group to another if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// - the new one has a higher priority</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// - the new entry has the same priority, but with docs where the old one had no docs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>()&lt;pri)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">        moveit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>()==pri)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">            moveit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightStringLiteral">"Member documentation for {} found several times in {} groups!\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightStringLiteral">"{}:{}: The member will remain in group {}, and won't be put into group {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">                md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( pri ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">                root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">                mgd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), fgd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">                );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (moveit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("removeMember\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">        mgd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a62090524551868d7e7016245b3800d1b">removeMember</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">        insertit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insertit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("insertMember found at %s line %d: %s: related %s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(md-&gt;getDefFileName()),md-&gt;getDefLine(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(md-&gt;name()),qPrint(root-&gt;relates));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> success = fgd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#aae7c161ee9febb2cb5ea6ed3dc74176e">insertMember</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (success)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("insertMember successful\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">          mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">setGroupDef</a>(fgd,pri,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,!root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *cdm = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a90092536a05578d258ca1381e3176c88">getClassDefOfAnonymousType</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">            cdm-&gt;<a href="/web-doxygen/docs/api/classes/classdefmutable/#a587dbea5e2811999a97fcedbb5619eff">setGroupDefForAllMembers</a>(fgd,pri,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() != 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>() &amp;&amp; mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>() &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adbdbd0e3d3630af579a02e97e162a328">isStrong</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;emd : mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *emdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(emd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (emdm &amp;&amp; emdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">                emdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">setGroupDef</a>(mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>(),mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">                                 mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a>(),mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">                                 mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">Entry::doc</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">MemberDef::enumFieldList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a90092536a05578d258ca1381e3176c88">MemberDef::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#acb9da3d6b3e2f3e8102ee9a3380c0746">MemberDef::getGroupFileName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">MemberDef::getGroupHasDocs</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">MemberDef::getGroupPri</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5d3b273949bc92e2b88e981aebc789bd">MemberDef::getGroupStartLine</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b">Grouping::GROUPING&#95;LOWEST</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#aae7c161ee9febb2cb5ea6ed3dc74176e">GroupDef::insertMember</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adbdbd0e3d3630af579a02e97e162a328">MemberDef::isStrong</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a62090524551868d7e7016245b3800d1b">GroupDef::removeMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">MemberDefMutable::setGroupDef</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#a587dbea5e2811999a97fcedbb5619eff">ClassDefMutable::setGroupDefForAllMembers</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a745ab96a81d2f900d75b86848050a8a7">addDefineDoc</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>.
</div>
</div>

### addModuleToGroups() {#a623caa8256bca5d7b0f640cd8182bcc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addModuleToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1493 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a623caa8256bca5d7b0f640cd8182bcc6">1493</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd &amp;&amp; gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a530747d47eb188ab2997190dcd78b8bb">addModule</a>(mod))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">      mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Module %s: in group %s\n",qPrint(mod-&gt;name()),gd-&gt;groupTitle());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#a530747d47eb188ab2997190dcd78b8bb">GroupDef::addModule</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>.
</div>
</div>

### addNamespaceToGroups() {#a035458fc750e2a32abad901b719f8392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addNamespaceToGroups (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1514 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a035458fc750e2a32abad901b719f8392">1514</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("root-&gt;groups.size()=%zu\n",root-&gt;groups.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &amp;g : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) gd=<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("group '%s' gd=%p\n",qPrint(g.groupname),(void*)gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd &amp;&amp; gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a69045b40b7deb5217d45b0bf1e183d7f">addNamespace</a>(nd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a> *ndm = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a>(nd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ndm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">        ndm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">makePartOfGroup</a>(gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Namespace %s: in group %s\n",qPrint(nd-&gt;name()),qPrint(gd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd &amp;&amp; g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> == <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>, root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Found non-existing group '{}' for the command '{}', ignoring command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">          g.<a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">groupname</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>( g.<a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">pri</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/groupdef/#a69045b40b7deb5217d45b0bf1e183d7f">GroupDef::addNamespace</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#ad683be469954d7f1aafc5f443a642506">Grouping::getGroupPriName</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING&#95;INGROUP</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a05e6a053a86cc2f588d065f3880801dc">Grouping::groupname</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ace7c1ad57b2a21941d7dd860e7e9c9fd">DefinitionMutable::makePartOfGroup</a>, <a href="/web-doxygen/docs/api/structs/grouping/#aead55d7198ceffe16cb82d2c114e4254">Grouping::pri</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>.
</div>
</div>

### createGroupDef() {#a78b23ceba36115840bc62b449edd9a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; GroupDef &gt; createGroupDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; refFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78b23ceba36115840bc62b449edd9a72">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;GroupDef&gt; <a href="#a78b23ceba36115840bc62b449edd9a72">createGroupDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;refFileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;GroupDefImpl&gt;(fileName,line,name,title,refFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a> and <a href="/web-doxygen/docs/api/classes/groupdef/#a4a476ffd1f00512dcb6f2f724bf23124">GroupDef::overrideGroupGraph</a>.
</div>
</div>

### groupClassesWithSameScope() {#a553cf15878cf6e6bdcecf5f8698f4349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Vec&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void groupClassesWithSameScope (Vec &amp; vec)</td>
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


<p>Definition at line 1788 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a553cf15878cf6e6bdcecf5f8698f4349">1788</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a553cf15878cf6e6bdcecf5f8698f4349">groupClassesWithSameScope</a>(Vec &amp;vec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done) </span><span class="doxyHighlightComment">// for each iteration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">    done=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;vec.size(); i++) </span><span class="doxyHighlightComment">// go through all items</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string qni = vec[i]-&gt;name().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> posi = qni.rfind(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (posi!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string scope = qni.substr(0,posi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if( vec.begin(), vec.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">            [&amp;](</span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::Ptr &amp;cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">            { return cd-&gt;name().str()==scope; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=vec.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> idx = std::distance(vec.begin(),it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;idx) </span><span class="doxyHighlightComment">// parent scope located after child scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// to avoid reordering elements with the same parent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// we skip to the last one with the same scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> k = idx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (k&lt;vec.size() &amp;&amp; vec[k]-&gt;name().str().substr(0,posi)==scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">              idx = k;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">              k++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// swap the items such that i is inserted after idx</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i; j&lt;idx; j++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">              std::swap(vec[j],vec[j+1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">            done=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (idx&lt;i &amp;&amp; vec[i-1]-&gt;name().str().substr(0,posi)!=scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// parent scope is found before the item, and the item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// has some other item with a different scope in front of it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// move idx to the end of range with the same scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (idx&lt;i &amp;&amp; vec[idx]-&gt;name().str().substr(0,posi)==scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">              idx++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// swap the items such that i is just after idx</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=idx; j&lt;i; j++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">              std::swap(vec[j],vec[j+1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">            done=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2a3b6387c4b99adde50e0751493d4990">GroupDefImpl::sortMemberLists</a>.
</div>
</div>

### hasNonReferenceNestedGroupRec() {#ae378b5ab8e781335e10e32435ae70ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasNonReferenceNestedGroupRec (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, int level)</td>
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


<p>Definition at line 1926 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae378b5ab8e781335e10e32435ae70ded">1926</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;30)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Possible recursive group relation while inside {}\n"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">isLinkableInProject</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;igd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">      found = found || <a href="#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a>(igd,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">GroupDef::getSubGroups</a>, <a href="#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a>, <a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">Definition::isLinkableInProject</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ccf5f8c86dd2dafa7306619f3a828dc">GroupDefImpl::isVisibleInHierarchy</a>.
</div>
</div>

### toGroupDef() {#a81b6ac5e79beed572376b9aebfa96da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GroupDef * toGroupDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1996 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81b6ac5e79beed572376b9aebfa96da5">1996</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *<a href="#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/groupdefimpl">GroupDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/structs/searchterm/#ac882a4444faaec272c4a80c69bc40035">SearchTerm::makeTitle</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad4c47fcf278c5cb6b23e82b584413ee8">DefinitionImpl::navigationPathAsString</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a4a476ffd1f00512dcb6f2f724bf23124">GroupDef::overrideGroupGraph</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#af8538fc61fb952e7681b9804247edc13">DefinitionImpl::pathFragment</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>.
</div>
</div>

### toGroupDef() {#af7300755cb300198b86b98757b2f8311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GroupDef * toGroupDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 2009 of file <a href="/web-doxygen/docs/api/files/src/groupdef-cpp">groupdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7300755cb300198b86b98757b2f8311">2009</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *<a href="#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/groupdefimpl">GroupDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
