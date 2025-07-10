---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/latexdocvisitor/activerowspan
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ActiveRowSpan` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct LatexDocVisitor::ActiveRowSpan { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a> (const DocHtmlCell &amp;c, size_t rs, size_t cs, size_t col)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87755be84cd1a593d4e2b3a1aa09b949">cell</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf99908d4f580429386410ab3f2cfd70">rowSpan</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39a5d5248845452b35637d2b546dc4c">colSpan</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7861de062ade2224edc16c7da880ab8">column</a></td>
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


<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ActiveRowSpan() {#a7bc83ee23ef8ea540331a7fb3951ffe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexDocVisitor::ActiveRowSpan::ActiveRowSpan (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c, size_t rs, size_t cs, size_t col)</td>
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



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> rs,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cs,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> col)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">        : <a href="#a87755be84cd1a593d4e2b3a1aa09b949">cell</a>(c), <a href="#adf99908d4f580429386410ab3f2cfd70">rowSpan</a>(rs), <a href="#af39a5d5248845452b35637d2b546dc4c">colSpan</a>(cs), <a href="#aa7861de062ade2224edc16c7da880ab8">column</a>(col) {}</span></span></div>

</div>


<p>References <a href="#a87755be84cd1a593d4e2b3a1aa09b949">cell</a>, <a href="#af39a5d5248845452b35637d2b546dc4c">colSpan</a>, <a href="#aa7861de062ade2224edc16c7da880ab8">column</a> and <a href="#adf99908d4f580429386410ab3f2cfd70">rowSpan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### cell {#a87755be84cd1a593d4e2b3a1aa09b949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocHtmlCell&amp; LatexDocVisitor::ActiveRowSpan::cell</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87755be84cd1a593d4e2b3a1aa09b949">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;<a href="#a87755be84cd1a593d4e2b3a1aa09b949">cell</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a>.</p>

</div>
</div>

### colSpan {#af39a5d5248845452b35637d2b546dc4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexDocVisitor::ActiveRowSpan::colSpan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af39a5d5248845452b35637d2b546dc4c">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#af39a5d5248845452b35637d2b546dc4c">colSpan</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a>.</p>

</div>
</div>

### column {#aa7861de062ade2224edc16c7da880ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexDocVisitor::ActiveRowSpan::column</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7861de062ade2224edc16c7da880ab8">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#aa7861de062ade2224edc16c7da880ab8">column</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a>.</p>

</div>
</div>

### rowSpan {#adf99908d4f580429386410ab3f2cfd70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexDocVisitor::ActiveRowSpan::rowSpan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf99908d4f580429386410ab3f2cfd70">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#adf99908d4f580429386410ab3f2cfd70">rowSpan</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7bc83ee23ef8ea540331a7fb3951ffe7">ActiveRowSpan</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
