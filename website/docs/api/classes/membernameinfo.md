---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/membernameinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `MemberNameInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class MemberNameInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/membername-h">src/membername.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberinfo">MemberInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bf3c5fa233fce3ddd551aff7e8a20a">Vec</a> = std::vector&lt; <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> = typename Vec::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a> = typename Vec::const_iterator</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f109f9b072511cb2988b9c53112d8ea">MemberNameInfo</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebf3be7d3e910bbb11f479fe92c97c3">memberName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d29481530127a9fe348f2ffa9372e1e">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c70eb8cd4221481fbb8bbba63270bc">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4053a00e03e07f9fb21f34fb5d548013">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21bb71e6701b35c0506cef5417e319ed">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a14c3fb07f0354cd657abdab632da86">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8bd29d751d01acfae24213f5aa74016">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb62a01d241db473ce1a83991c9e1958">back</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1dc8c626a98660202c3017a68ffa5e7">back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e46bd54ac0e21b1e51bc48cae1e783">front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd10009e8a177aba2603f93f427d237">front</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c155a8de478f85cd0e551e37d07bdb">push_back</a> (Ptr &amp;&amp;p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfc27742277de33731d8c35b234e7f1">erase</a> (iterator pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ebb253dbf1c056f2242402dd068fd7">m_name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a09bf3c5fa233fce3ddd551aff7e8a20a">Vec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a></td>
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


Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a2d4bc1c4bd6f8a15bd74a83c110be20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberNameInfo::const_iterator =  typename Vec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#ac34a9f52c33c9d933f82b809262f3c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberNameInfo::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Ptr {#af53dcec82c09b660d181864c608bcd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberNameInfo::Ptr =  std::unique_ptr&lt;MemberInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af53dcec82c09b660d181864c608bcd6a">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> = std::unique_ptr&lt;MemberInfo&gt;;</span></span></div>

</div>

</div>
</div>

### Vec {#a09bf3c5fa233fce3ddd551aff7e8a20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberNameInfo::Vec =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09bf3c5fa233fce3ddd551aff7e8a20a">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a09bf3c5fa233fce3ddd551aff7e8a20a">Vec</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemberNameInfo() {#a9f109f9b072511cb2988b9c53112d8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberNameInfo::MemberNameInfo (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f109f9b072511cb2988b9c53112d8ea">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9f109f9b072511cb2988b9c53112d8ea">MemberNameInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name) : <a href="#a78ebb253dbf1c056f2242402dd068fd7">m_name</a>(name) {}</span></span></div>

</div>


Reference <a href="#a78ebb253dbf1c056f2242402dd068fd7">m\_name</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#adb62a01d241db473ce1a83991c9e1958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ptr &amp; MemberNameInfo::back ()</td>
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



Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb62a01d241db473ce1a83991c9e1958">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;<a href="#adb62a01d241db473ce1a83991c9e1958">back</a>()                            { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.back();    }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

### back() {#ad1dc8c626a98660202c3017a68ffa5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ptr &amp; MemberNameInfo::back ()</td>
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



Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1dc8c626a98660202c3017a68ffa5e7">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;<a href="#ad1dc8c626a98660202c3017a68ffa5e7">back</a>()</span><span class="doxyHighlightKeyword"> const                </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.back();    }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

### begin() {#a8d29481530127a9fe348f2ffa9372e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberNameInfo::begin ()</td>
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



Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d29481530127a9fe348f2ffa9372e1e">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> <a href="#a8d29481530127a9fe348f2ffa9372e1e">begin</a>()                       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.begin();   }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>.
</div>
</div>

### begin() {#a4053a00e03e07f9fb21f34fb5d548013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator MemberNameInfo::begin ()</td>
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



Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4053a00e03e07f9fb21f34fb5d548013">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a> <a href="#a4053a00e03e07f9fb21f34fb5d548013">begin</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.begin();   }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

### empty() {#a4a14c3fb07f0354cd657abdab632da86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberNameInfo::empty ()</td>
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



Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a14c3fb07f0354cd657abdab632da86">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4a14c3fb07f0354cd657abdab632da86">empty</a>()</span><span class="doxyHighlightKeyword"> const                     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.empty();   }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>.
</div>
</div>

### end() {#aa2c70eb8cd4221481fbb8bbba63270bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberNameInfo::end ()</td>
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



Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2c70eb8cd4221481fbb8bbba63270bc">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> <a href="#aa2c70eb8cd4221481fbb8bbba63270bc">end</a>()                         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.end();     }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>.
</div>
</div>

### end() {#a21bb71e6701b35c0506cef5417e319ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator MemberNameInfo::end ()</td>
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



Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21bb71e6701b35c0506cef5417e319ed">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2d4bc1c4bd6f8a15bd74a83c110be20c">const_iterator</a> <a href="#a21bb71e6701b35c0506cef5417e319ed">end</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.end();     }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

### erase() {#aebfc27742277de33731d8c35b234e7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberNameInfo::erase (<a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> pos)</td>
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



Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebfc27742277de33731d8c35b234e7f1">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> <a href="#aebfc27742277de33731d8c35b234e7f1">erase</a>(<a href="#ac34a9f52c33c9d933f82b809262f3c4d">iterator</a> pos)           { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.erase(pos); }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>.
</div>
</div>

### front() {#ad5e46bd54ac0e21b1e51bc48cae1e783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ptr &amp; MemberNameInfo::front ()</td>
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



Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5e46bd54ac0e21b1e51bc48cae1e783">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;<a href="#ad5e46bd54ac0e21b1e51bc48cae1e783">front</a>()                           { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.front();   }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>.
</div>
</div>

### front() {#a0fd10009e8a177aba2603f93f427d237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ptr &amp; MemberNameInfo::front ()</td>
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



Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fd10009e8a177aba2603f93f427d237">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;<a href="#a0fd10009e8a177aba2603f93f427d237">front</a>()</span><span class="doxyHighlightKeyword"> const               </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.front();   }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

### memberName() {#a1ebf3be7d3e910bbb11f479fe92c97c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberNameInfo::memberName ()</td>
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



Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ebf3be7d3e910bbb11f479fe92c97c3">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1ebf3be7d3e910bbb11f479fe92c97c3">memberName</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78ebb253dbf1c056f2242402dd068fd7">m_name</a>; }</span></span></div>

</div>


Reference <a href="#a78ebb253dbf1c056f2242402dd068fd7">m\_name</a>.
</div>
</div>

### push\_back() {#a73c155a8de478f85cd0e551e37d07bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberNameInfo::push_back (<a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;&amp; p)</td>
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



Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73c155a8de478f85cd0e551e37d07bdb">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a73c155a8de478f85cd0e551e37d07bdb">push_back</a>(<a href="#af53dcec82c09b660d181864c608bcd6a">Ptr</a> &amp;&amp;p)                { <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.push_back(std::move(p)); }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>.
</div>
</div>

### size() {#aa8bd29d751d01acfae24213f5aa74016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MemberNameInfo::size ()</td>
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



Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa8bd29d751d01acfae24213f5aa74016">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#aa8bd29d751d01acfae24213f5aa74016">size</a>()</span><span class="doxyHighlightKeyword"> const                    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>.size();    }</span></span></div>

</div>


Reference <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m\_members</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_members {#ad8330b83d4e2dcaed60e4727b8868f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec MemberNameInfo::m_members</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8330b83d4e2dcaed60e4727b8868f04">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a09bf3c5fa233fce3ddd551aff7e8a20a">Vec</a> <a href="#ad8330b83d4e2dcaed60e4727b8868f04">m_members</a>;</span></span></div>

</div>


Referenced by <a href="#adb62a01d241db473ce1a83991c9e1958">back</a>, <a href="#ad1dc8c626a98660202c3017a68ffa5e7">back</a>, <a href="#a8d29481530127a9fe348f2ffa9372e1e">begin</a>, <a href="#a4053a00e03e07f9fb21f34fb5d548013">begin</a>, <a href="#a4a14c3fb07f0354cd657abdab632da86">empty</a>, <a href="#aa2c70eb8cd4221481fbb8bbba63270bc">end</a>, <a href="#a21bb71e6701b35c0506cef5417e319ed">end</a>, <a href="#aebfc27742277de33731d8c35b234e7f1">erase</a>, <a href="#ad5e46bd54ac0e21b1e51bc48cae1e783">front</a>, <a href="#a0fd10009e8a177aba2603f93f427d237">front</a>, <a href="#a73c155a8de478f85cd0e551e37d07bdb">push\_back</a> and <a href="#aa8bd29d751d01acfae24213f5aa74016">size</a>.
</div>
</div>

### m\_name {#a78ebb253dbf1c056f2242402dd068fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberNameInfo::m_name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78ebb253dbf1c056f2242402dd068fd7">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a78ebb253dbf1c056f2242402dd068fd7">m_name</a>;</span></span></div>

</div>


Referenced by <a href="#a1ebf3be7d3e910bbb11f479fe92c97c3">memberName</a> and <a href="#a9f109f9b072511cb2988b9c53112d8ea">MemberNameInfo</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
