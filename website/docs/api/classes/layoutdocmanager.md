---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/layoutdocmanager
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LayoutDocManager` Class Reference

<p>Singleton providing access to the (user configurable) layout of the documentation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LayoutDocManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/layout-h">src/layout.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LayoutPart { <a href="#aee13a925ea1f915c542ecd7f579ebc94">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693e1185a1fe8a78b6cc4404c68c91ca">~LayoutDocManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/layout-h/#ac96b78f2694c0e0203d69214041dba8a">LayoutDocEntryList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0416762a9e6d28e22e8f46102579f32">docEntries</a> (LayoutPart part) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of <a href="/web-doxygen/docs/api/structs/layoutdocentry">LayoutDocEntry</a>'s in representation order for a given page identified by <em>part</em>. <a href="#ae0416762a9e6d28e22e8f46102579f32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the (invisible) root of the navigation tree. <a href="#ad70cfcbfc25b8f303a59cd8f76c61465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597bb9c69db0e2c07006194a6cb87b27">createChildNavEntry</a> (LayoutNavEntry *root, LayoutNavEntry::Kind k, bool vs, const QCString &amp;bf, const QCString &amp;tl, const QCString &amp;intro)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>append a new node as a child to root. <a href="#a597bb9c69db0e2c07006194a6cb87b27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a> (const QCString &amp;fileName, const char *data=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a user provided layout. <a href="#aa40638bbc3b82e1b24a760b6e5dff877">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920748477d4262faf758d21ddbe2329d">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0dd224201ce703af34ab0e0b373d1d7">majorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b614882970c7338a04e440ae18b75c">minorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab020a031a90d2c24b29130dc405c9e3b">addEntry</a> (LayoutPart p, LayoutDocEntryPtr &amp;&amp;e)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e0ccdf2bfa4ba53166b139561b3392">mergeNavEntries</a> (LayoutDocManager &amp;manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93105c3e85cce37f624edb1bfae60a52">mergeDocEntries</a> (const QCString &amp;fileName, LayoutDocManager &amp;manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/layoutdocmanager/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5781f6331f76419686e20d9307ec9171">d</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bc2288833b8769bd03e47c58fbba6a">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to this singleton. <a href="#a87bc2288833b8769bd03e47c58fbba6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2544b39188e0657e88357b3d21f2bb96">partToString</a> (int k)</td>
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

<p>Singleton providing access to the (user configurable) layout of the documentation.</p>

<p>Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### LayoutPart {#aee13a925ea1f915c542ecd7f579ebc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LayoutDocManager::LayoutPart </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PART_SPECIFICATIONS<a id="aee13a925ea1f915c542ecd7f579ebc94adcb5f6a36a4f1332c2c0418017f3c8cd"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/layout-h/#aebfde55eabd92537d8c00cfad89e9452">267</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PSPEC(x,y) x y,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee13a925ea1f915c542ecd7f579ebc94adcb5f6a36a4f1332c2c0418017f3c8cd">268</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aee13a925ea1f915c542ecd7f579ebc94adcb5f6a36a4f1332c2c0418017f3c8cd">PART_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef PSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LayoutParser {#aaa876b66a7f0c8c8766635655c0dff49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definition at line 306 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa876b66a7f0c8c8766635655c0dff49">306</a></span><span class="doxyLineContent"><span class="doxyHighlight">    friend class <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a>;</span></span></div>

</div>


References <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a>, <a href="/web-doxygen/docs/api/files/src/layout-h/#ad2711841592974bc20e2390475c4c45d">printLayout</a> and <a href="/web-doxygen/docs/api/files/src/layout-h/#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a>.

Referenced by <a href="#a920748477d4262faf758d21ddbe2329d">init</a>, <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a> and <a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LayoutDocManager() {#ade9c88ce93dd67220115ba975c7078b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocManager::LayoutDocManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 302 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1407 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade9c88ce93dd67220115ba975c7078b1">1407</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager::LayoutDocManager</a>() : <a href="#a5781f6331f76419686e20d9307ec9171">d</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/layoutdocmanager/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.

Referenced by <a href="#a87bc2288833b8769bd03e47c58fbba6a">instance</a>, <a href="#a93105c3e85cce37f624edb1bfae60a52">mergeDocEntries</a>, <a href="#a15e0ccdf2bfa4ba53166b139561b3392">mergeNavEntries</a> and <a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### ~LayoutDocManager() {#a693e1185a1fe8a78b6cc4404c68c91ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocManager::~LayoutDocManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 303 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1411 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a693e1185a1fe8a78b6cc4404c68c91ca">1411</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a693e1185a1fe8a78b6cc4404c68c91ca">LayoutDocManager::~LayoutDocManager</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createChildNavEntry() {#a597bb9c69db0e2c07006194a6cb87b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry * LayoutDocManager::createChildNavEntry (<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> * root, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> k, bool vs, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bf, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; intro)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>append a new node as a child to root.</p>

<p>Declaration at line 289 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1451 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a597bb9c69db0e2c07006194a6cb87b27">1451</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *<a href="#a597bb9c69db0e2c07006194a6cb87b27">LayoutDocManager::createChildNavEntry</a>(<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> k,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> vs,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tl,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;intro)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a> = &amp;<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;rootNav;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ptr = std::make_unique&lt;LayoutNavEntry&gt;(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,k,vs,bf,tl,intro);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> child = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>-&gt;appendChild(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> child;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5781f6331f76419686e20d9307ec9171">d</a> and <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>.
</div>
</div>

### docEntries() {#ae0416762a9e6d28e22e8f46102579f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LayoutDocEntryList &amp; LayoutDocManager::docEntries (<a href="#aee13a925ea1f915c542ecd7f579ebc94">LayoutPart</a> part)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the list of <a href="/web-doxygen/docs/api/structs/layoutdocentry">LayoutDocEntry</a>'s in representation order for a given page identified by <em>part</em>.</p>

<p>Declaration at line 284 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1441 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0416762a9e6d28e22e8f46102579f32">1441</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/layout-h/#ac96b78f2694c0e0203d69214041dba8a">LayoutDocEntryList</a> &amp;<a href="#ae0416762a9e6d28e22e8f46102579f32">LayoutDocManager::docEntries</a>(<a href="#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a> part)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(part)];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.
</div>
</div>

### init() {#a920748477d4262faf758d21ddbe2329d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::init ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 294 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1415 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a920748477d4262faf758d21ddbe2329d">1415</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a> layoutParser(<a href="#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> handlers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a> = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrs) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#aec3d26d68ff653ee286a16533ba98560">startElement</a>(name,attrs); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">endElement</a>   = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#acbe58d70dfdb7b82544b3c6390a3ffa9">endElement</a>(name); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">error</a>        = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a4bec4061de53be8bf8585c227844737d">error</a>(fileName,lineNr,<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> parser(handlers);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">  layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a27bcf121a54f586745ec706921dc955b">setDocumentLocator</a>(&amp;parser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> layoutFile = </span><span class="doxyHighlightStringLiteral">"layout_default.xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> layout_default = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(layoutFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">  parser.<a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">parse</a>(layoutFile,layout_default.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Entering"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,layoutFile); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Finished"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,layoutFile); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;majorVersion = layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a75f8b4ee2ad4de9bf624c5427ce75fae">majorVersion</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;minorVersion = layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a9883cc99cb60a2b4c3c4135521ddc12c">minorVersion</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5781f6331f76419686e20d9307ec9171">d</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#acbe58d70dfdb7b82544b3c6390a3ffa9">LayoutParser::endElement</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">XMLHandlers::endElement</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a4bec4061de53be8bf8585c227844737d">LayoutParser::error</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">XMLHandlers::error</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="#a87bc2288833b8769bd03e47c58fbba6a">instance</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex&#95;xml</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a75f8b4ee2ad4de9bf624c5427ce75fae">LayoutParser::majorVersion</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a9883cc99cb60a2b4c3c4135521ddc12c">LayoutParser::minorVersion</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">XMLParser::parse</a>, <a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a27bcf121a54f586745ec706921dc955b">LayoutParser::setDocumentLocator</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aec3d26d68ff653ee286a16533ba98560">LayoutParser::startElement</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">XMLHandlers::startElement</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.
</div>
</div>

### majorVersion() {#aa0dd224201ce703af34ab0e0b373d1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutDocManager::majorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 295 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1529 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0dd224201ce703af34ab0e0b373d1d7">1529</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa0dd224201ce703af34ab0e0b373d1d7">LayoutDocManager::majorVersion</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;majorVersion;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.
</div>
</div>

### minorVersion() {#aa5b614882970c7338a04e440ae18b75c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutDocManager::minorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 296 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1534 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5b614882970c7338a04e440ae18b75c">1534</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa5b614882970c7338a04e440ae18b75c">LayoutDocManager::minorVersion</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;minorVersion;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.
</div>
</div>

### parse() {#aa40638bbc3b82e1b24a760b6e5dff877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * data=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Parses a user provided layout.</p>

<p>Declaration at line 293 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1468 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa40638bbc3b82e1b24a760b6e5dff877">1468</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("============ LayoutDocManager::parse(%s)\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> layoutDocManager;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a> layoutParser(layoutDocManager);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> handlers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a> = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrs) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#aec3d26d68ff653ee286a16533ba98560">startElement</a>(name,attrs); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">endElement</a>   = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#acbe58d70dfdb7b82544b3c6390a3ffa9">endElement</a>(name); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">error</a>        = [&amp;layoutParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fn,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>) { layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a4bec4061de53be8bf8585c227844737d">error</a>(fn,lineNr,<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> parser(handlers);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">  layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a27bcf121a54f586745ec706921dc955b">setDocumentLocator</a>(&amp;parser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">  parser.<a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">parse</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">               data ? data : <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(fileName).data(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { <a href="/web-doxygen/docs/api/classes/debuglex/#aba76b8a3cf651c0fc03dc731a8f880e0">DebugLex::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>,</span><span class="doxyHighlightStringLiteral">"Entering"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName)); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { <a href="/web-doxygen/docs/api/classes/debuglex/#aba76b8a3cf651c0fc03dc731a8f880e0">DebugLex::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>,</span><span class="doxyHighlightStringLiteral">"Finished"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName)); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// version in the user defined layout overrides default one</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;majorVersion = layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a75f8b4ee2ad4de9bf624c5427ce75fae">majorVersion</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;minorVersion = layoutParser.<a href="/web-doxygen/docs/api/classes/layoutparser/#a9883cc99cb60a2b4c3c4135521ddc12c">minorVersion</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// merge missing parts of the default layout into the user defined layout</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// For now merging in defaults has been disabled for navigation entries</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// to avoid "extra entries" for projects that work with partial layout files.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//mergeNavEntries(layoutDocManager);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for compatibility reasons we only merge defaults when the user defined layout has at least version 2 or higher</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;majorVersion&gt;=2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a93105c3e85cce37f624edb1bfae60a52">mergeDocEntries</a>(fileName,layoutDocManager);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  layoutDocManager.<a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// replace default layout with merged layout</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries.swap(layoutDocManager.<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;rootNav.swap(layoutDocManager.<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;rootNav);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5781f6331f76419686e20d9307ec9171">d</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#acbe58d70dfdb7b82544b3c6390a3ffa9">LayoutParser::endElement</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">XMLHandlers::endElement</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a4bec4061de53be8bf8585c227844737d">LayoutParser::error</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">XMLHandlers::error</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a>, <a href="#aaa876b66a7f0c8c8766635655c0dff49">LayoutParser</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex&#95;xml</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a75f8b4ee2ad4de9bf624c5427ce75fae">LayoutParser::majorVersion</a>, <a href="#a93105c3e85cce37f624edb1bfae60a52">mergeDocEntries</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a9883cc99cb60a2b4c3c4135521ddc12c">LayoutParser::minorVersion</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">XMLParser::parse</a>, <a href="/web-doxygen/docs/api/classes/debuglex/#aba76b8a3cf651c0fc03dc731a8f880e0">DebugLex::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a27bcf121a54f586745ec706921dc955b">LayoutParser::setDocumentLocator</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aec3d26d68ff653ee286a16533ba98560">LayoutParser::startElement</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">XMLHandlers::startElement</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.
</div>
</div>

### rootNavEntry() {#ad70cfcbfc25b8f303a59cd8f76c61465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry * LayoutDocManager::rootNavEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns the (invisible) root of the navigation tree.</p>

<p>Declaration at line 287 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1446 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad70cfcbfc25b8f303a59cd8f76c61465">1446</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a>* <a href="#ad70cfcbfc25b8f303a59cd8f76c61465">LayoutDocManager::rootNavEntry</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;rootNav;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="#a15e0ccdf2bfa4ba53166b139561b3392">mergeNavEntries</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aeecbfdef5946563004101a2aeffa82a3">writeFileMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab2818fb513d9fdb38f3ff8e75848f388">writeIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#add40a3a8212464c4914efbeba3d529a1">writeMenuData</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a64d6048a9f49fef7b55ddef8526ac819">writeModuleMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad62d481af92d88b79731ae76f4e821b3">writeNamespaceMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addEntry() {#ab020a031a90d2c24b29130dc405c9e3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::addEntry (<a href="#aee13a925ea1f915c542ecd7f579ebc94">LayoutPart</a> p, <a href="/web-doxygen/docs/api/files/src/layout-h/#a8eee761b1994aff7959da6f51904e021">LayoutDocEntryPtr</a> &amp;&amp; e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 298 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1462 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab020a031a90d2c24b29130dc405c9e3b">1462</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab020a031a90d2c24b29130dc405c9e3b">LayoutDocManager::addEntry</a>(<a href="#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a> p,<a href="/web-doxygen/docs/api/files/src/layout-h/#a8eee761b1994aff7959da6f51904e021">LayoutDocEntryPtr</a> &amp;&amp;e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;docEntry = <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(p)];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">  docEntry.push_back(std::move(e)); </span><span class="doxyHighlightComment">// add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.
</div>
</div>

### mergeDocEntries() {#a93105c3e85cce37f624edb1bfae60a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::mergeDocEntries (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, <a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp; manager)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 300 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1721 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93105c3e85cce37f624edb1bfae60a52">1721</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a93105c3e85cce37f624edb1bfae60a52">LayoutDocManager::mergeDocEntries</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,<a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries.size(); i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightComment">//printf("========= part %zu\n",i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/layout-cpp/#afd0221363a595085db047f038eb1c4bd">mergeDocEntryLists</a>(fileName,other.<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries[i],<a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5781f6331f76419686e20d9307ec9171">d</a>, <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> and <a href="/web-doxygen/docs/api/files/src/layout-cpp/#afd0221363a595085db047f038eb1c4bd">mergeDocEntryLists</a>.

Referenced by <a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a>.
</div>
</div>

### mergeNavEntries() {#a15e0ccdf2bfa4ba53166b139561b3392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::mergeNavEntries (<a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp; manager)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 299 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1633 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15e0ccdf2bfa4ba53166b139561b3392">1633</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a15e0ccdf2bfa4ba53166b139561b3392">LayoutDocManager::mergeNavEntries</a>(<a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a0b8f8966ef09819dbf2186a63317a5ec">mergeNavTreeNodesRec</a>(other.<a href="#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a>(),<a href="#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a0b8f8966ef09819dbf2186a63317a5ec">mergeNavTreeNodesRec</a> and <a href="#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a>.
</div>
</div>

### removeInvisibleDocEntries() {#adc3fc9bbc6ce9d55bf4abc261f4a066c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutDocManager::removeInvisibleDocEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 301 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1509 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">1509</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">LayoutDocManager::removeInvisibleDocEntries</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remove invisible entries</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;list : <a href="#a5781f6331f76419686e20d9307ec9171">d</a>-&gt;docEntries)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = list.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (it!=list.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*it==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || !(*it)-&gt;visible())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">        it = list.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">        ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5781f6331f76419686e20d9307ec9171">d</a>.

Referenced by <a href="#a920748477d4262faf758d21ddbe2329d">init</a> and <a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### d {#a5781f6331f76419686e20d9307ec9171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; LayoutDocManager::d</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 305 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5781f6331f76419686e20d9307ec9171">305</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;<a href="/web-doxygen/docs/api/classes/layoutdocmanager/private">Private</a>&gt; <a href="#a5781f6331f76419686e20d9307ec9171">d</a>;</span></span></div>

</div>


Referenced by <a href="#ab020a031a90d2c24b29130dc405c9e3b">addEntry</a>, <a href="#a597bb9c69db0e2c07006194a6cb87b27">createChildNavEntry</a>, <a href="#ae0416762a9e6d28e22e8f46102579f32">docEntries</a>, <a href="#a920748477d4262faf758d21ddbe2329d">init</a>, <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a>, <a href="#aa0dd224201ce703af34ab0e0b373d1d7">majorVersion</a>, <a href="#a93105c3e85cce37f624edb1bfae60a52">mergeDocEntries</a>, <a href="#aa5b614882970c7338a04e440ae18b75c">minorVersion</a>, <a href="#aa40638bbc3b82e1b24a760b6e5dff877">parse</a>, <a href="#adc3fc9bbc6ce9d55bf4abc261f4a066c">removeInvisibleDocEntries</a> and <a href="#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a87bc2288833b8769bd03e47c58fbba6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocManager &amp; LayoutDocManager::instance ()</td>
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
<p>Returns a reference to this singleton.</p>

<p>Declaration at line 272 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1435 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87bc2288833b8769bd03e47c58fbba6a">1435</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> &amp; <a href="#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ade9c88ce93dd67220115ba975c7078b1">LayoutDocManager</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f5e5eea90b425337d1ce80a48c7fe59">addMembersToIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a4a1478cb4a1ba9d12204b6061241a6ec">ClassDefImpl::countAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a65da06e287af8337fb13d15a3e976cc8">ModuleDefImpl::countVisibleMembers</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a3994dde65ff9904e985305b79c8e8026">NamespaceDefImpl::countVisibleMembers</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a80477acfb036d1755b9b393698cd8f69">ClassDefImpl::getTitleForMemberListType</a>, <a href="#a920748477d4262faf758d21ddbe2329d">init</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ad2711841592974bc20e2390475c4c45d">printLayout</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2629ab8d1e500f052c39bde8a52711af">ClassDefImpl::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad9ade8c43232b499c51f41859454a664">ClassDefImpl::writeAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a783230ed87aae779b1e405abfe5b9954">ClassDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae849568cb2c125f1d3a89a41e3ded5d7">ClassDefImpl::writeDocumentationContents</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aeecbfdef5946563004101a2aeffa82a3">writeFileMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab2818fb513d9fdb38f3ff8e75848f388">writeIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#add40a3a8212464c4914efbeba3d529a1">writeMenuData</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a64d6048a9f49fef7b55ddef8526ac819">writeModuleMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a98f02f28ab5ec9b1a51543a7ef4ba1ab">writeModuleMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad62d481af92d88b79731ae76f4e821b3">writeNamespaceMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a56fd407208531785588bf3482ac098b9">writeNamespaceMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3d1a9e0be346811184a93c9337e12f93">ClassDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a1dcc947390f3bc72c7deac0f523f5b7c">DirDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6426eeffa8f2ff5b40e5c0a24f82ea46">FileDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a610be194f2a4ad7dbcee5265e45b9058">GroupDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a57b6528e8c47fc04f0ca3aa71fbb1dcb">ModuleDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4bbc6ca08fcd6e9ccbfd15cdf3bfbf1d">NamespaceDefImpl::writeTagFile</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.
</div>
</div>

### partToString() {#a2544b39188e0657e88357b3d21f2bb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LayoutDocManager::partToString (int k)</td>
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


<p>Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2544b39188e0657e88357b3d21f2bb96">273</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::string <a href="#a2544b39188e0657e88357b3d21f2bb96">partToString</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> k)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (k)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PSPEC(x,y) case x: return #x; break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aee13a925ea1f915c542ecd7f579ebc94adcb5f6a36a4f1332c2c0418017f3c8cd">PART_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef PSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to satisfy compiler</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#aee13a925ea1f915c542ecd7f579ebc94adcb5f6a36a4f1332c2c0418017f3c8cd">PART&#95;SPECIFICATIONS</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ad2711841592974bc20e2390475c4c45d">printLayout</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
