---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/layout-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `layout.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include &lt;vector&gt;
#include &lt;utility&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentry">LayoutDocEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class representing a piece of a documentation page. <a href="/web-doxygen/docs/api/structs/layoutdocentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents of a piece of a documentation page without configurable parts. <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentrysection">LayoutDocEntrySection</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdecl">LayoutDocEntryMemberDecl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents of a member declaration list with configurable title and subtitle. <a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdecl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdef">LayoutDocEntryMemberDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents of a member definition list with configurable title. <a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for the layout of a navigation item at the top of the HTML pages. <a href="/web-doxygen/docs/api/structs/layoutnaventry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Singleton providing access to the (user configurable) layout of the documentation. <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eee761b1994aff7959da6f51904e021">LayoutDocEntryPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/layoutdocentry">LayoutDocEntry</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96b78f2694c0e0203d69214041dba8a">LayoutDocEntryList</a> = std::vector&lt; <a href="#a8eee761b1994aff7959da6f51904e021">LayoutDocEntryPtr</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> = std::vector&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a> (const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2711841592974bc20e2390475c4c45d">printLayout</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926e734275b0dc81972209981523a37a">ENTRY_SPECIFICATIONS</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(x)&nbsp;&nbsp;&nbsp;x,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(x)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf75144f663adec2c99d8ebae1a2efc9">NAV_SPECIFICATIONS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44a766908bd6f2e5040c265c688851e">NSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;x y,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44a766908bd6f2e5040c265c688851e">NSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ac3f780c1045f6b2c067f7d9ee19e7">PART_SPECIFICATIONS</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;x y,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
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

## Typedefs

### LayoutDocEntryList {#ac96b78f2694c0e0203d69214041dba8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LayoutDocEntryList =  std::vector&lt;LayoutDocEntryPtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac96b78f2694c0e0203d69214041dba8a">148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ac96b78f2694c0e0203d69214041dba8a">LayoutDocEntryList</a> = std::vector&lt;LayoutDocEntryPtr&gt;;</span></span></div>

</div>

</div>
</div>

### LayoutDocEntryPtr {#a8eee761b1994aff7959da6f51904e021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LayoutDocEntryPtr =  std::unique_ptr&lt;LayoutDocEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8eee761b1994aff7959da6f51904e021">147</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a8eee761b1994aff7959da6f51904e021">LayoutDocEntryPtr</a>  = std::unique_ptr&lt;LayoutDocEntry&gt;;</span></span></div>

</div>

</div>
</div>

### LayoutNavEntryList {#a9c5fd65331b31fb2296490bbff30b043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LayoutNavEntryList =  std::vector&lt; std::unique_ptr&lt;LayoutNavEntry&gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c5fd65331b31fb2296490bbff30b043">152</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> = std::vector&lt; std::unique_ptr&lt;LayoutNavEntry&gt; &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### printLayout() {#ad2711841592974bc20e2390475c4c45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 310 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1820 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/layout-cpp/#ad2711841592974bc20e2390475c4c45d">1820</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ad2711841592974bc20e2390475c4c45d">printLayout</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extraIndent = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mgr = <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"Layout version {}.{}\n"</span><span class="doxyHighlight">,mgr.majorVersion(),mgr.minorVersion());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"Part: Navigation index\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : mgr.rootNavEntry()-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>(e.get(),2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; LayoutDocManager::NrParts; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"\nPart: {}\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a2544b39188e0657e88357b3d21f2bb96">LayoutDocManager::partToString</a>(i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;lde : mgr.docEntries(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a> *ldes = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(lde.get()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lde-&gt;kind() == LayoutDocEntry::MemberDeclEnd || lde-&gt;kind() == LayoutDocEntry::MemberDefEnd) extraIndent = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"  {}kind: {}, visible={}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">           extraIndent? </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,lde-&gt;entryToString(), ldes-&gt;visible());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lde-&gt;kind() == LayoutDocEntry::MemberDeclStart || lde-&gt;kind() == LayoutDocEntry::MemberDefStart) extraIndent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdecl">LayoutDocEntryMemberDecl</a> *lmdecl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdecl">LayoutDocEntryMemberDecl</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(lde.get()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"  {}complex kind: {}, visible={}, type: {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">           extraIndent? </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,lde-&gt;entryToString(),lmdecl-&gt;visible(),lmdecl-&gt;type.to_string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdef">LayoutDocEntryMemberDef</a> *lmdef = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutdocentrymemberdef">LayoutDocEntryMemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(lde.get()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"  {}complex kind: {}, visible={}, type: {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">           extraIndent? </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,lde-&gt;entryToString(),lmdef-&gt;visible(),lmdef-&gt;type.to_string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightComment">// should not happen</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>,0,</span><span class="doxyHighlightStringLiteral">"  {}not handled kind: {}\n"</span><span class="doxyHighlight">,extraIndent? </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,lde-&gt;entryToString());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a2544b39188e0657e88357b3d21f2bb96">LayoutDocManager::partToString</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a> and <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aaa876b66a7f0c8c8766635655c0dff49">LayoutDocManager::LayoutParser</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.
</div>
</div>

### writeDefaultLayoutFile() {#a8ccb483586d18bd75a15720be22f90cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDefaultLayoutFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 309 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1732 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/layout-cpp/#a8ccb483586d18bd75a15720be22f90cb">1732</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c6662051d765cb0a355382ab05c14a1">openOutputFile</a>(fileName,f))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> layout_default = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"layout_default.xml"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(layout_default,</span><span class="doxyHighlightStringLiteral">"$doxygenversion"</span><span class="doxyHighlight">,getDoxygenVersion());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to open file {} for writing!\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c6662051d765cb0a355382ab05c14a1">openOutputFile</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aaa876b66a7f0c8c8766635655c0dff49">LayoutDocManager::LayoutParser</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ENTRY&#95;SPECIFICATIONS {#a926e734275b0dc81972209981523a37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY_SPECIFICATIONS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">              /&#42; <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aea8045a0a6c688b0635e3caccc408a1446">Generic</a> items for all pages &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberGroups) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberDeclStart) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberDeclEnd) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberDecl) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberDefStart) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(MemberDefEnd) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(BriefDesc) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(DetailedDesc) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(AuthorSection) \
              /&#42; <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da9bd81329febf6efe22788e03ddeaf0af">Class</a> specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassIncludes) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassInlineClasses) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassInheritanceGraph) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassNestedClasses) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassCollaborationGraph) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassAllMembersLink) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ClassUsedFiles) \
              /&#42; <a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843cad99a604c79ce3c2e76a2f43488d5d4c3">Concept</a> specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ConceptDefinition) \
              /&#42; <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449dab3ba0fe968ce39dcfc6fe8cc0f1b02da">Namespace</a> specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceNestedNamespaces) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceNestedConstantGroups) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceClasses) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceConcepts) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceInterfaces) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceStructs) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceExceptions) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(NamespaceInlineClasses) \
              /&#42; <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da0b27918290ff5323bea1e3b78a9cf04e">File</a> specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileClasses) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileConcepts) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileInterfaces) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileStructs) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileExceptions) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileConstantGroups) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileNamespaces) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileIncludes) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileIncludeGraph) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileIncludedByGraph) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileSourceLink) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(FileInlineClasses) \
              /&#42; C++20 <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09abf17ac149e2e7a530c677e9bd51d3fd2">Modules</a> &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ModuleExports) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ModuleClasses) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ModuleConcepts) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(ModuleUsedFiles) \
              /&#42; <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da03937134cedab9078be39a77ee3a48a0">Group</a> specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupClasses) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupConcepts) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupModules) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupInlineClasses) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupNamespaces) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupDirs) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupNestedGroups) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupFiles) \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupGraph) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(GroupPageDocs) \
              /&#42; Directory specific items &#42;/ \
              <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(DirSubDirs) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(DirFiles) <a href="#a01157ce01f2cb28fc582a7c4fd23e80d">ESPEC</a>(DirGraph)
</div>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a926e734275b0dc81972209981523a37a">35</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ENTRY_SPECIFICATIONS \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Generic items for all pages */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(MemberGroups) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(MemberDeclStart) ESPEC(MemberDeclEnd) ESPEC(MemberDecl) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(MemberDefStart) ESPEC(MemberDefEnd) ESPEC(MemberDef) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(BriefDesc) ESPEC(DetailedDesc) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(AuthorSection) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Class specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ClassIncludes) ESPEC(ClassInlineClasses) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ClassInheritanceGraph) ESPEC(ClassNestedClasses) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ClassCollaborationGraph) ESPEC(ClassAllMembersLink) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ClassUsedFiles) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Concept specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ConceptDefinition) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Namespace specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(NamespaceNestedNamespaces) ESPEC(NamespaceNestedConstantGroups) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(NamespaceClasses) ESPEC(NamespaceConcepts) ESPEC(NamespaceInterfaces) ESPEC(NamespaceStructs) ESPEC(NamespaceExceptions) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(NamespaceInlineClasses) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* File specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(FileClasses) ESPEC(FileConcepts) ESPEC(FileInterfaces) ESPEC(FileStructs) ESPEC(FileExceptions) ESPEC(FileConstantGroups) ESPEC(FileNamespaces) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(FileIncludes) ESPEC(FileIncludeGraph) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(FileIncludedByGraph) ESPEC(FileSourceLink) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(FileInlineClasses) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* C++20 Modules */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(ModuleExports) ESPEC(ModuleClasses) ESPEC(ModuleConcepts) ESPEC(ModuleUsedFiles) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Group specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(GroupClasses) ESPEC(GroupConcepts) ESPEC(GroupModules) ESPEC(GroupInlineClasses) ESPEC(GroupNamespaces) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(GroupDirs) ESPEC(GroupNestedGroups) ESPEC(GroupFiles) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(GroupGraph) ESPEC(GroupPageDocs) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              </span><span class="doxyHighlightComment">/* Directory specific items */</span><span class="doxyHighlightPreprocessor"> \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">              ESPEC(DirSubDirs) ESPEC(DirFiles) ESPEC(DirGraph)</span></span></div>

</div>

</div>
</div>

### ESPEC {#a01157ce01f2cb28fc582a7c4fd23e80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ESPEC(x)&nbsp;&nbsp;&nbsp;x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01157ce01f2cb28fc582a7c4fd23e80d">68</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ESPEC(x) x,</span></span></div>

</div>

</div>
</div>

### ESPEC {#a01157ce01f2cb28fc582a7c4fd23e80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ESPEC(x)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01157ce01f2cb28fc582a7c4fd23e80d">68</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ESPEC(x) x,</span></span></div>

</div>

</div>
</div>

### NAV&#95;SPECIFICATIONS {#abf75144f663adec2c99d8ebae1a2efc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NAV_SPECIFICATIONS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf75144f663adec2c99d8ebae1a2efc9">157</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NAV_SPECIFICATIONS \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(None, = -1) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(MainPage,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Pages,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Modules,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ModuleList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ModuleMembers,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Topics,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Namespaces,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(NamespaceList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(NamespaceMembers,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Concepts,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Classes,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ClassList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ClassIndex,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ClassHierarchy,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ClassMembers,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Interfaces,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(InterfaceList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(InterfaceIndex,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(InterfaceHierarchy,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Structs,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(StructList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(StructIndex,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Exceptions,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ExceptionList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ExceptionIndex,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(ExceptionHierarchy,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Files,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(FileList,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(FileGlobals,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(Examples,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(User,) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      NSPEC(UserGroup,)</span></span></div>

</div>

</div>
</div>

### NSPEC {#af44a766908bd6f2e5040c265c688851e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NSPEC(x, y)&nbsp;&nbsp;&nbsp;x y,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af44a766908bd6f2e5040c265c688851e">194</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NSPEC(x,y) x y,</span></span></div>

</div>

</div>
</div>

### NSPEC {#af44a766908bd6f2e5040c265c688851e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NSPEC(x, y)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af44a766908bd6f2e5040c265c688851e">194</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NSPEC(x,y) x y,</span></span></div>

</div>

</div>
</div>

### PART&#95;SPECIFICATIONS {#a02ac3f780c1045f6b2c067f7d9ee19e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PART_SPECIFICATIONS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(Undefined, = -1)     \
  <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da9bd81329febf6efe22788e03ddeaf0af">Class</a>,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843cad99a604c79ce3c2e76a2f43488d5d4c3">Concept</a>,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449dab3ba0fe968ce39dcfc6fe8cc0f1b02da">Namespace</a>,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da0b27918290ff5323bea1e3b78a9cf04e">File</a>,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da03937134cedab9078be39a77ee3a48a0">Group</a>,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(Directory,) <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449dae55f75a29310d7b60f7ac1d390c8ae42">Module</a>,)       \
  <a href="#aebfde55eabd92537d8c00cfad89e9452">PSPEC</a>(NrParts,)
</div>
</dd>
</dl>

<p>Definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02ac3f780c1045f6b2c067f7d9ee19e7">256</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PART_SPECIFICATIONS \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  PSPEC(Undefined, = -1)     \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  PSPEC(Class,) PSPEC(Concept,) PSPEC(Namespace,) PSPEC(File,) PSPEC(Group,) PSPEC(Directory,) PSPEC(Module,)       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  PSPEC(NrParts,)</span></span></div>

</div>

</div>
</div>

### PSPEC {#aebfde55eabd92537d8c00cfad89e9452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PSPEC(x, y)&nbsp;&nbsp;&nbsp;x y,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebfde55eabd92537d8c00cfad89e9452">267</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PSPEC(x,y) x y,</span></span></div>

</div>

</div>
</div>

### PSPEC {#aebfde55eabd92537d8c00cfad89e9452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PSPEC(x, y)&nbsp;&nbsp;&nbsp;case x: return #x; break;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebfde55eabd92537d8c00cfad89e9452">267</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PSPEC(x,y) x y,</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
