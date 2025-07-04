---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/classdef-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `classdef.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstdio&gt;
#include &lt;algorithm&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/diagram-h">diagram.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/example-h">example.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotclassgraph-h">dotclassgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotrunner-h">dotrunner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdefimpl">ClassDefImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of the <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> interface. <a href="/web-doxygen/docs/api/classes/classdefimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdefaliasimpl">ClassDefAliasImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a> (const ClassDef *cd, const ArgumentLists *actualParams, uint32_t *actualParamIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a> (const ClassDef *cd, bool includeScope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f124efb6cc839e90c9681f9be40eee6">getCompoundTypeString</a> (SrcLangExt lang, ClassDef::CompoundType compType, bool isJavaEnum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4fc67011e33756c70e8cc33572d59a">createClassDef</a> (const QCString &amp;fileName, int startLine, int startColumn, const QCString &amp;name, ClassDef::CompoundType ct, const QCString &amp;ref, const QCString &amp;fName, bool isSymbol, bool isJavaEnum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create a new <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> object. <a href="#aad4fc67011e33756c70e8cc33572d59a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5773d03b68726ad9d01bb1c7dc5f0e">createClassDefAlias</a> (const Definition *newScope, const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a> (OutputList &amp;ol, const BaseClassDef &amp;bcd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a> (const Definition *d, ArgumentLists &amp;result, QCString &amp;name, SrcLangExt lang)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a> (const ClassDef *cd, int level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8390a828ac301fcfe39d600bfa242297">isStandardFunc</a> (const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c64550144b1c5be3dfa3e79ad1a2ac1">toClassDef</a> (DefinitionMutable *md)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2d9148971973811ca545c8990b1951">toClassDef</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a> (const QCString &amp;n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a> (const BaseClassList &amp;bcl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9fad8d7ee7f78e152b542bcd38061d">classVisibleInIndex</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a> (const ClassDef *cd, const ClassDef *bcd, int level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a> (const ClassDef *cd, const ClassDef *bcd, Protection prot, int level)</td>
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

### classHasVisibleChildren() {#af0c88e52d4d7424c0840a23a522dc330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool classHasVisibleChildren (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5489 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0c88e52d4d7424c0840a23a522dc330">5489</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5490</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5491</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> bcl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5492</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()==SrcLangExt::VHDL) </span><span class="doxyHighlightComment">// reverse baseClass/subClass relation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5494</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>().empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5496</span><span class="doxyLineContent"><span class="doxyHighlight">    bcl=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5497</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5498</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5499</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>().empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5501</span><span class="doxyLineContent"><span class="doxyHighlight">    bcl=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5502</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5503</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : bcl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5505</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5506</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bcd.classDef-&gt;isVisibleInHierarchy())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5507</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5508</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5509</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5510</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5511</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5512</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>.</p>

</div>
</div>

### classHasVisibleRoot() {#aa17b12d6a1e62b6d01659a5c9857aa4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool classHasVisibleRoot (const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp; bcl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5478 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">5478</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;bcl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5479</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5480</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : bcl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5481</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5482</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5484</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5485</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5487</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">ClassDef::isVisibleInHierarchy</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a2c46ad2d91b685cb40efdc4ffeb85e61">DotGfxHierarchyTable::addClassList</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a821e7b508daf7d6a89ee6bc4634fce12">countClassesInTreeList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>.</p>

</div>
</div>

### classInheritedProtectionLevel() {#ad1c7d957765b81dbe423423b2f5e5b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Protection classInheritedProtectionLevel (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot, int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5548 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1c7d957765b81dbe423423b2f5e5b48">5548</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> <a href="#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bcd,<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5549</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bcd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">categoryOf</a>()) </span><span class="doxyHighlightComment">// use class that is being extended in case of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// an Objective-C category</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5552</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5553</span><span class="doxyLineContent"><span class="doxyHighlight">    bcd=bcd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">categoryOf</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5554</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==bcd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5556</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5557</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> exit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5558</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==256)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5560</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5561</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Internal inconsistency: found class {} seem to have a recursive "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5562</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"inheritance relation! Please send a bug report to doxygen@gmail.com\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5563</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prot!=Protection::Private)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5565</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5566</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcdi : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5567</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5568</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> baseProt = <a href="#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>(bcdi.classDef,bcd,bcdi.prot,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5569</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (baseProt==Protection::Private)        prot=Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (baseProt==Protection::Protected) prot=Protection::Protected;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5571</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5572</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5573</span><span class="doxyLineContent"><span class="doxyHighlight">exit:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("classInheritedProtectionLevel(%s,%s)=%d\n",qPrint(cd-&gt;name()),qPrint(bcd-&gt;name()),prot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5575</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> prot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5576</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">ClassDef::categoryOf</a>, <a href="#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>.</p>

</div>
</div>

### classVisibleInIndex() {#abf9fad8d7ee7f78e152b542bcd38061d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool classVisibleInIndex (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5514 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf9fad8d7ee7f78e152b542bcd38061d">5514</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abf9fad8d7ee7f78e152b542bcd38061d">classVisibleInIndex</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5515</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> allExternals = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(ALLEXTERNALS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (allExternals &amp;&amp; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()) || cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">isLinkableInProject</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5518</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a> and <a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">Definition::isLinkableInProject</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>.</p>

</div>
</div>

### createClassDef() {#aad4fc67011e33756c70e8cc33572d59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ClassDef &gt; createClassDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int startLine, int startColumn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, bool isSymbol, bool isJavaEnum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Factory method to create a new <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> object.</p>

<p>Definition at line 559 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad4fc67011e33756c70e8cc33572d59a">559</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ClassDef&gt; <a href="#aad4fc67011e33756c70e8cc33572d59a">createClassDef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSymbol,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isJavaEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;ClassDefImpl&gt;(fileName,startLine,startColumn,name,ct,ref,fName,isSymbol,isJavaEnum);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a> and <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>.</p>

</div>
</div>

### createClassDefAlias() {#a9e5773d03b68726ad9d01bb1c7dc5f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ClassDef &gt; createClassDefAlias (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * newScope, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e5773d03b68726ad9d01bb1c7dc5f0e">788</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ClassDef&gt; <a href="#a9e5773d03b68726ad9d01bb1c7dc5f0e">createClassDefAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> acd = std::make_unique&lt;ClassDefAliasImpl&gt;(newScope,cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("cd name=%s localName=%s qualifiedName=%s qualifiedNameWith=%s displayName()=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(acd-&gt;name()),qPrint(acd-&gt;localName()),qPrint(acd-&gt;qualifiedName()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(acd-&gt;qualifiedNameWithTemplateParameters()),qPrint(acd-&gt;displayName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> acd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ada4744c5dd6e3339cf4de2b8d2b50717">ClassDefAliasImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a> and <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>.</p>

</div>
</div>

### getClass() {#a9682735bd2cf0656eaa944f8b3e364a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * getClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Get a class definition given its name. Returns nullptr if the class is not found.</p>


<p>Definition at line 5472 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9682735bd2cf0656eaa944f8b3e364a2">5472</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5473</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5476</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8e0a72feb96a836fa1650fe1b9f1e39a">findClassWithinClassContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a7a69e84416f85b6fd78f21b6d5effb67">getClassMutable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aa2b4c58062de6e3075936abc6c29dd7e">getTemplateArgumentsFromName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9905c57ded9f8f4db3bbe658e510f781">MemberDefImpl::isDocumentedFriendClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.</p>

</div>
</div>

### getCompoundTypeString() {#a0f124efb6cc839e90c9681f9be40eee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getCompoundTypeString (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> compType, bool isJavaEnum)</td>
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



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f124efb6cc839e90c9681f9be40eee6">146</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0f124efb6cc839e90c9681f9be40eee6">getCompoundTypeString</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang,<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> compType,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isJavaEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (compType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">ClassDef::Struct</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09">ClassDef::Union</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"union"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"interface"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"protocol"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">ClassDef::Category</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"category"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">ClassDef::Exception</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"exception"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:                  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (compType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> isJavaEnum ? </span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">ClassDef::Struct</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"struct"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09">ClassDef::Union</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"union"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> lang==SrcLangExt::ObjC ? </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"interface"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"protocol"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">ClassDef::Category</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"category"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">ClassDef::Exception</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"exception"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939aaf2c9d4d2eaa6e6a614d7bd164a29c0e">ClassDef::Service</a>:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"service"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a34f6a5dd42307d62a5fe3038b245a667">ClassDef::Singleton</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"singleton"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:                  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">ClassDef::Category</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">ClassDef::Exception</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939aaf2c9d4d2eaa6e6a614d7bd164a29c0e">ClassDef::Service</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a34f6a5dd42307d62a5fe3038b245a667">ClassDef::Singleton</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">ClassDef::Struct</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09">ClassDef::Union</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a143f754de317ae2e44ea6fc5994b42f5">ClassDefImpl::compoundTypeString</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>.</p>

</div>
</div>

### hasNonReferenceSuperClassRec() {#a566364d58b27f9c2324d9caeda697818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasNonReferenceSuperClassRec (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, int level)</td>
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



<p>Definition at line 3480 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a566364d58b27f9c2324d9caeda697818">3480</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3481</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=!cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>() &amp;&amp; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">isLinkableInProject</a>() &amp;&amp; !cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// we're done if this class is not a reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3486</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ibcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3488</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bcd=ibcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;256)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3491</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3492</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Possible recursive class relation while inside {} and looking for base class {}\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),bcd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3494</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// recurse into the super class branch</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3496</span><span class="doxyLineContent"><span class="doxyHighlight">    found = found || <a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>(bcd,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3498</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3499</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// look for template instances that might have non-reference super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3500</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cil : bcd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3ceb3e484b62599117b5eb424c10fd10">getTemplateInstances</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3501</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3502</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// recurse into the template instance branch</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3503</span><span class="doxyLineContent"><span class="doxyHighlight">        found = <a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>(cil.classDef,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3504</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3505</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3506</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3507</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3508</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3509</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3510</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3511</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3512</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3513</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3ceb3e484b62599117b5eb424c10fd10">ClassDef::getTemplateInstances</a>, <a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">Definition::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#af9d9f7406ae882c2d8598e503a7309c5">ClassDefImpl::hasNonReferenceSuperClass</a> and <a href="#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>.</p>

</div>
</div>

### isStandardFunc() {#a8390a828ac301fcfe39d600bfa242297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStandardFunc (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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



<p>Definition at line 3718 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8390a828ac301fcfe39d600bfa242297">3718</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8390a828ac301fcfe39d600bfa242297">isStandardFunc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3719</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3720</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()==</span><span class="doxyHighlightStringLiteral">"operator="</span><span class="doxyHighlight"> || </span><span class="doxyHighlightComment">// assignment operator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3721</span><span class="doxyLineContent"><span class="doxyHighlight">         md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a196a099fba755a0586625635e40e9c58">isConstructor</a>() ||     </span><span class="doxyHighlightComment">// constructor</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3722</span><span class="doxyLineContent"><span class="doxyHighlight">         md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0807e7d46f56761eb33db77778289c11">isDestructor</a>();        </span><span class="doxyHighlightComment">// destructor</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3723</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/memberdef/#a196a099fba755a0586625635e40e9c58">MemberDef::isConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0807e7d46f56761eb33db77778289c11">MemberDef::isDestructor</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>.</p>

</div>
</div>

### makeDisplayName() {#a5893e87386908aa95d70f866f340b8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeDisplayName (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, bool includeScope)</td>
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



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5893e87386908aa95d70f866f340b8a8">107</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> includeScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool optimizeOutputForJava = Config_getBool(OPTIMIZE_OUTPUT_JAVA);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool vhdlOpt = Config_getBool(OPTIMIZE_OUTPUT_VHDL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    n = <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (includeScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      n=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad488bfd3800b79d9984bb2e11aadde2f">qualifiedNameWithTemplateParameters</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      n=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    n = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sep=<a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sep!=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    n=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(n,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,sep);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>()==<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a> &amp;&amp; n.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    n=</span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight">+n.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(n.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2)+</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">ClassDef::compoundType</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">ClassDef::Protocol</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ad488bfd3800b79d9984bb2e11aadde2f">ClassDef::qualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a9e0a300a44e814de013db11434e9568c">ClassDefAliasImpl::displayName</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#addaab92fcc22df4e75a64ce97787e79c">ClassDefImpl::displayName</a>.</p>

</div>
</div>

### makeQualifiedNameWithTemplateParameters() {#a0327bf0462f4c2efcdc2103a587e560e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeQualifiedNameWithTemplateParameters (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> * actualParams, uint32_t * actualParamIndex)</td>
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



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0327bf0462f4c2efcdc2103a587e560e">56</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> *actualParams,uint32_t *actualParamIndex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool optimizeOutputJava = Config_getBool(OPTIMIZE_OUTPUT_JAVA);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hideScopeNames = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HIDE_SCOPE_NAMES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("qualifiedNameWithTemplateParameters() localName=%s\n",qPrint(cd-&gt;localName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ocd=<a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      scName = ocd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad488bfd3800b79d9984bb2e11aadde2f">qualifiedNameWithTemplateParameters</a>(actualParams,actualParamIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hideScopeNames)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      scName = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopeSeparator = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) scName+=scopeSeparator;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a> = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">localName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">)!=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> clName = cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  scName+=clName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang!=SrcLangExt::CSharp &amp;&amp; !cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>().<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (actualParams &amp;&amp; *actualParamIndex&lt;actualParams-&gt;size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al = actualParams-&gt;<a href="/web-doxygen/docs/api/classes/argumentlist/#acc1e900dbe37733434eef1d805ee61ba">at</a>(*actualParamIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">        scName+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>(al,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      (*actualParamIndex)++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">        scName+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(),lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("qualifiedNameWithTemplateParameters: scope=%s qualifiedName=%s\n",qPrint(name()),qPrint(scName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> scName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/argumentlist/#acc1e900dbe37733434eef1d805ee61ba">ArgumentList::at</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>, <a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">Definition::localName</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ad488bfd3800b79d9984bb2e11aadde2f">ClassDef::qualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a>, <a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a2e7190f6e1928c0e8d70d6cc013cc401">ClassDefAliasImpl::qualifiedNameWithTemplateParameters</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1925788b5849231e417820b15533e023">ClassDefImpl::qualifiedNameWithTemplateParameters</a>.</p>

</div>
</div>

### minClassDistance() {#a649670159a00e0a1c323df1b40bf01e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int minClassDistance (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5524 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a649670159a00e0a1c323df1b40bf01e6">5524</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bcd,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5525</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a225f155c4a7035d82bee0b83dec4ae50">maxInheritanceDepth</a> = 100000;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5527</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bcd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">categoryOf</a>()) </span><span class="doxyHighlightComment">// use class that is being extended in case of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// an Objective-C category</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5529</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5530</span><span class="doxyLineContent"><span class="doxyHighlight">    bcd=bcd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">categoryOf</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5531</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==bcd) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==256)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5534</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5535</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"class {} seem to have a recursive inheritance relation!\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5536</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5537</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> m=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a225f155c4a7035d82bee0b83dec4ae50">maxInheritanceDepth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5539</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcdi : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5540</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mc=<a href="#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a>(bcdi.classDef,bcd,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5542</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mc&lt;m) m=mc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (m&lt;0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5544</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5545</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5546</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">ClassDef::categoryOf</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a225f155c4a7035d82bee0b83dec4ae50">maxInheritanceDepth</a>, <a href="#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a490c49dd8d15cdb49e53083c6b21e441">ClassDefImpl::getMemberByName</a> and <a href="#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a>.</p>

</div>
</div>

### searchTemplateSpecs() {#ab40d758b9f5159a2d26d0b59efe7e36d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void searchTemplateSpecs (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> &amp; result, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</td>
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



<p>Definition at line 1467 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab40d758b9f5159a2d26d0b59efe7e36d">1467</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>(</span><span class="doxyHighlightComment">/*in*/</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightComment">/*out*/</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> &amp;result,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightComment">/*out*/</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightComment">/*in*/</span><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>(d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),result,name,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=<a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) name+=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> clName = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">localName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (clName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">      clName = clName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(clName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">    name+=clName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a> = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">localName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">)!=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>().<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      result.push_back(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">        name+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(),lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    name+=d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">Definition::localName</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a>, <a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>.</p>


<p>Referenced by <a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>.</p>

</div>
</div>

### toClassDef() {#ac7e9d22a4c24e745c1ab16d0af527da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * toClassDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5418 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7e9d22a4c24e745c1ab16d0af527da2">5418</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5419</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefimpl">ClassDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefaliasimpl">ClassDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5421</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5423</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5425</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5427</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5428</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad11603424a7299217c0999bb963b0b5b">ClassDefImpl::addInnerCompound</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a34803fafd2b7ff3f593f4c9a97c59f2d">NamespaceDefImpl::addInnerCompound</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a92e0ed943a60680559a637016d45b14f">MemberDefImpl::addListReference</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a67d97db3c717b89b9a6211ae48e9273b">findModuleDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/structs/ftvhelp/private/#a0bed14c4bee93963b64e37bb6532aad8">FTVHelp::Private::generateTree</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ab1366e62ee0c1a0e917952eb62b3fcab">ClassDefAliasImpl::getCdAlias</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2dfea6a5bbab656f1806e4cd5fb1487b">ClassDefImpl::getTemplateParameterLists</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a263db4e9ffc625509018045b0345b31c">MemberDefImpl::moveTo</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad4c47fcf278c5cb6b23e82b584413ee8">DefinitionImpl::navigationPathAsString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad1f69f6dd5f57e967a880988a49aa56e">scopeIsTemplate</a>, <a href="#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a8da5e564ca5debbb07a26fb91c0fc3d6">updateCallContextForSmartPointer</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.</p>

</div>
</div>

### toClassDef() {#a0c64550144b1c5be3dfa3e79ad1a2ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * toClassDef (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5430 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c64550144b1c5be3dfa3e79ad1a2ac1">5430</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5431</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5433</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefimpl">ClassDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5434</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5436</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5438</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5440</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5441</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>.</p>

</div>
</div>

### toClassDef() {#adc2d9148971973811ca545c8990b1951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * toClassDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5443 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc2d9148971973811ca545c8990b1951">5443</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5444</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5445</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefimpl">ClassDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefaliasimpl">ClassDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5446</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5448</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5450</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5451</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5452</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5453</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### toClassDefMutable() {#a2d0bf73f7801534e7e2b6e5fc03ed6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDefMutable * toClassDefMutable (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5455 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d0bf73f7801534e7e2b6e5fc03ed6f5">5455</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *<a href="#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5456</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5457</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/classdefimpl">ClassDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5458</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5460</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5462</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5464</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5465</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a48485218477ceb4bff6608fb8c7d1d45">ModuleDefImpl::addClassToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a6e2ffe69d7a921c13b6d0e16918a250d">ModuleManager::addClassToModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4219b5e9c9b107b0b5380459e032a142">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a97d3881f19cc6d4afb3d7a7376ec222b">ClassDefImpl::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa48018d80bff3d0e37cd1ff67c5972f8">ClassDefImpl::addTypeConstraint</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae643312889aa3507462f9adfecf49e40">buildCompleteMemberLists</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4130a395a6948c0202fc85ac018a6236">computeMemberReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab8681769cd2f027fbf46a4836d3825e9">VhdlDocGen::computeVhdlComponentRelations</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a8635f06556c6af82953ab2e0797db8a6">ClassDefImpl::countInheritedDecMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a777a8d72bf18dc4c572fb70528ec18b2">countMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a518c45b338059b959b548810b82c2a01">createTemplateInstanceMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a21cfa81a6854b108ab53153e9db19d3c">distributeClassGroupRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5f7021c47224d92c76642ad8501d5eb6">distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a90bc9ccd867058973acec037b08218a6">findTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a712bc5bd97d995f02595622efbfcc5e4">generateClassDocs</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a61b713e61e238a458b7a64ef221973a4">generateNamespaceClassDocs</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4d6e5d5ab5365b572eb407c4fa86aee1">MemberDefImpl::getClassDefMutable</a>, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a7a69e84416f85b6fd78f21b6d5effb67">getClassMutable</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a02e748da779cf061b14c27d976efdb65">insertMemberAlias</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af3eab25ba334db0ed299983b354a89cb">ClassDefImpl::insertTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a17517cd0cef3a68bed83908e1cdea718">ClassDefImpl::insertUsedFile</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad091d341c14ea4fbd41ca45921d5b75f">mergeCategories</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad1f7e120d2a503b8b15e6a68002d0dd5">ClassDefImpl::mergeMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#ab3249c001539f0f9de46a3ec8098fbea">SymbolResolver::resolveClassMutable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a50691a7238e6347682eedc24405e27ab">setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a510e0aa934874b28d777e3e1d1c13341">sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fb5141ea8877090d564026636d81a14">ClassDefImpl::writeInheritedMemberDeclarations</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.</p>

</div>
</div>

### writeInheritanceSpecifier() {#aa1221bfb5b21c047427a269f0caef930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInheritanceSpecifier (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/structs/baseclassdef">BaseClassDef</a> &amp; bcd)</td>
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



<p>Definition at line 1406 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1221bfb5b21c047427a269f0caef930">1406</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/baseclassdef">BaseClassDef</a> &amp;bcd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bcd.<a href="/web-doxygen/docs/api/structs/baseclassdef/#ab5a986f56300bfa53f7c4cff58196294">prot</a>!=Protection::Public || bcd.<a href="/web-doxygen/docs/api/structs/baseclassdef/#a844100c6fcd90233e01e52fc92107464">virt</a>!=Specifier::Normal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a848e77a8fd7af578497f7ee1ec163b98">startTypewriter</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" ["</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> sl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (bcd.<a href="/web-doxygen/docs/api/structs/baseclassdef/#ab5a986f56300bfa53f7c4cff58196294">prot</a>==Protection::Protected) sl.emplace_back(</span><span class="doxyHighlightStringLiteral">"protected"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bcd.<a href="/web-doxygen/docs/api/structs/baseclassdef/#ab5a986f56300bfa53f7c4cff58196294">prot</a>==Protection::Private)   sl.emplace_back(</span><span class="doxyHighlightStringLiteral">"private"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (bcd.<a href="/web-doxygen/docs/api/structs/baseclassdef/#a844100c6fcd90233e01e52fc92107464">virt</a>==Specifier::Virtual)    sl.emplace_back(</span><span class="doxyHighlightStringLiteral">"virtual"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">      first=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad83302c45e73f387c9dc13789df012f7">endTypewriter</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad83302c45e73f387c9dc13789df012f7">OutputList::endTypewriter</a>, <a href="/web-doxygen/docs/api/structs/baseclassdef/#ab5a986f56300bfa53f7c4cff58196294">BaseClassDef::prot</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a848e77a8fd7af578497f7ee1ec163b98">OutputList::startTypewriter</a> and <a href="/web-doxygen/docs/api/structs/baseclassdef/#a844100c6fcd90233e01e52fc92107464">BaseClassDef::virt</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
