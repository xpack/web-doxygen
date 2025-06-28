---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/grouping
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Grouping` Struct Reference

<p><a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> info. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct Grouping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/types-h">src/types.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GroupPri_t { <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> priority. <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdaf504afe84841e327f6c8e2b76e29">Grouping</a> (const QCString &amp;gn, GroupPri_t p)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e6a053a86cc2f588d065f3880801dc">groupname</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>name of the group <a href="#a05e6a053a86cc2f588d065f3880801dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead55d7198ceffe16cb82d2c114e4254">pri</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>priority of this definition <a href="#aead55d7198ceffe16cb82d2c114e4254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad683be469954d7f1aafc5f443a642506">getGroupPriName</a> (GroupPri_t priority)</td>
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

<p><a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> info.</p>

<p>Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### GroupPri&#95;t {#a9f0ec5ab376b083ebe3274ea79fd2d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum Grouping::GroupPri_t </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p><a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> priority.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_LOWEST<a id="a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_AUTO_WEAK<a id="a9f0ec5ab376b083ebe3274ea79fd2d70aa59227c8fa39faf56ebc4c06e08d4d84"></a></td>
<td class="doxyEnumItemDescription"><p>membership in group was defined via @weakgroup (= GROUPING_LOWEST)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_AUTO_ADD<a id="a9f0ec5ab376b083ebe3274ea79fd2d70a44f89332beea02ebc5d56bcb71a081ba"></a></td>
<td class="doxyEnumItemDescription"><p>membership in group was defined via @add[to]group</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_AUTO_DEF<a id="a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f"></a></td>
<td class="doxyEnumItemDescription"><p>membership in group was defined via @defgroup</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_AUTO_HIGHEST<a id="a9f0ec5ab376b083ebe3274ea79fd2d70ab0dee71675bf90a137537784427e2956"></a></td>
<td class="doxyEnumItemDescription"><p> (= GROUPING_AUTO_DEF)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_INGROUP<a id="a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb"></a></td>
<td class="doxyEnumItemDescription"><p>membership in group was defined by @ingroup</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GROUPING_HIGHEST<a id="a9f0ec5ab376b083ebe3274ea79fd2d70adca997c0931955d0ff0b9e23d14a9d2a"></a></td>
<td class="doxyEnumItemDescription"><p> (= GROUPING_INGROUP)</p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/types-h/#l00229">229</a> of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b">GROUPING_LOWEST</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70aa59227c8fa39faf56ebc4c06e08d4d84">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70aa59227c8fa39faf56ebc4c06e08d4d84">GROUPING_AUTO_WEAK</a> = <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a251075fcb0324e4f5f3d7bc8767ca06b">GROUPING_LOWEST</a>,     </span><span class="doxyHighlightComment">//!&lt; membership in group was defined via \@weakgroup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a44f89332beea02ebc5d56bcb71a081ba">233</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a44f89332beea02ebc5d56bcb71a081ba">GROUPING_AUTO_ADD</a>,     </span><span class="doxyHighlightComment">//!&lt; membership in group was defined via \@add[to]group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f">GROUPING_AUTO_DEF</a>,     </span><span class="doxyHighlightComment">//!&lt; membership in group was defined via \@defgroup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab0dee71675bf90a137537784427e2956">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab0dee71675bf90a137537784427e2956">GROUPING_AUTO_HIGHEST</a> = <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f">GROUPING_AUTO_DEF</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">GROUPING_INGROUP</a>,      </span><span class="doxyHighlightComment">//!&lt; membership in group was defined by \@ingroup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0ec5ab376b083ebe3274ea79fd2d70adca997c0931955d0ff0b9e23d14a9d2a">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70adca997c0931955d0ff0b9e23d14a9d2a">GROUPING_HIGHEST</a> = <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">GROUPING_INGROUP</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Grouping() {#abfdaf504afe84841e327f6c8e2b76e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Grouping::Grouping (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; gn, <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a> p)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/types-h/#l00256">256</a> of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abfdaf504afe84841e327f6c8e2b76e29">256</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abfdaf504afe84841e327f6c8e2b76e29">Grouping</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;gn, <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a> p ) : <a href="#a05e6a053a86cc2f588d065f3880801dc">groupname</a>(gn), <a href="#aead55d7198ceffe16cb82d2c114e4254">pri</a>(p) {}</span></span></div>

</div>


References <a href="#a05e6a053a86cc2f588d065f3880801dc">groupname</a> and <a href="#aead55d7198ceffe16cb82d2c114e4254">pri</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### groupname {#a05e6a053a86cc2f588d065f3880801dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Grouping::groupname</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>name of the group</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/types-h/#l00257">257</a> of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05e6a053a86cc2f588d065f3880801dc">257</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a05e6a053a86cc2f588d065f3880801dc">groupname</a>;   </span><span class="doxyHighlightComment">//!&lt; name of the group</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a118dacc3a4f140d0321d4fb170c8e8f6">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a> and <a href="#abfdaf504afe84841e327f6c8e2b76e29">Grouping</a>.
</div>
</div>

### pri {#aead55d7198ceffe16cb82d2c114e4254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GroupPri_t Grouping::pri</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>priority of this definition</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/types-h/#l00258">258</a> of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aead55d7198ceffe16cb82d2c114e4254">258</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a> <a href="#aead55d7198ceffe16cb82d2c114e4254">pri</a>;       </span><span class="doxyHighlightComment">//!&lt; priority of this definition</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a> and <a href="#abfdaf504afe84841e327f6c8e2b76e29">Grouping</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getGroupPriName() {#ad683be469954d7f1aafc5f443a642506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * Grouping::getGroupPriName (<a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a> priority)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/types-h/#l00240">240</a> of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad683be469954d7f1aafc5f443a642506">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ad683be469954d7f1aafc5f443a642506">getGroupPriName</a>( <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70">GroupPri_t</a> priority )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">( priority )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70aa59227c8fa39faf56ebc4c06e08d4d84">GROUPING_AUTO_WEAK</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"@weakgroup"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a44f89332beea02ebc5d56bcb71a081ba">GROUPING_AUTO_ADD</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"@addtogroup"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f">GROUPING_AUTO_DEF</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"@defgroup"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">GROUPING_INGROUP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"@ingroup"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"???"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a44f89332beea02ebc5d56bcb71a081ba">GROUPING&#95;AUTO&#95;ADD</a>, <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70ab767fc9fe6f874c09362fd1350738f7f">GROUPING&#95;AUTO&#95;DEF</a>, <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70aa59227c8fa39faf56ebc4c06e08d4d84">GROUPING&#95;AUTO&#95;WEAK</a> and <a href="#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">GROUPING&#95;INGROUP</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/types-h">types.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
