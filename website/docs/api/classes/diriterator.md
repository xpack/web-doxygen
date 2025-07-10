---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/diriterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DirIterator` Class Reference



## Declaration

<div class="doxyDeclaration">
class DirIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dir-h">src/dir.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144120a41958226a725d3d2533a7c783">value_type</a> = <a href="/web-doxygen/docs/api/classes/direntry">DirEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1220d59d9dfb89d43504c5e9466364d7">difference_type</a> = std::ptrdiff_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11200453a8ff0bf95cbaedb50dff510">pointer</a> = <a href="#a144120a41958226a725d3d2533a7c783">value_type</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2715f06935759c6e7996c6cc26691514">reference</a> = <a href="#a144120a41958226a725d3d2533a7c783">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce3bd2279cef163ec80d5b74da4276d">iterator_category</a> = std::input_iterator_tag</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c037aa57ccb12f75092ea55062c933e">Dir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9285cecfcff40959eed73e1da7d139da">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde2fab844e4f384c5d715f06f0835f4">operator!=</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c94b68ae7d5509e621425954c7fc50">begin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0550a128905c4e07b633d437992b002">end</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> (const DirIterator &amp;it)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb4e1054c2150c4d5f159876a91266a9">DirIterator</a> (DirIterator &amp;&amp;it)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a049e2a4e5b8b273e56b0bcbdf32cf4">DirIterator</a> (const std::string &amp;path)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d20623f235e252893d994957ec2a9f6">~DirIterator</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6af63e61d1cd8a695c70210d1200696">operator=</a> (const DirIterator &amp;it)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c1406fad2fbd8ede290b7ba0874130">operator=</a> (DirIterator &amp;&amp;it)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21357cd7836791a40ecd6db98fa864f2">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#a144120a41958226a725d3d2533a7c783">value_type</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54db35ff62b7ab4045a593b92ac8780d">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#a144120a41958226a725d3d2533a7c783">value_type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6956f8bf3894639348454cb62784c74f">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a></td>
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


<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### difference\_type {#a1220d59d9dfb89d43504c5e9466364d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirIterator::difference_type =  std::ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1220d59d9dfb89d43504c5e9466364d7">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a1220d59d9dfb89d43504c5e9466364d7">difference_type</a> = std::ptrdiff_t;</span></span></div>

</div>

</div>
</div>

### iterator\_category {#a1ce3bd2279cef163ec80d5b74da4276d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirIterator::iterator_category =  std::input_iterator_tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ce3bd2279cef163ec80d5b74da4276d">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a1ce3bd2279cef163ec80d5b74da4276d">iterator_category</a> = std::input_iterator_tag;</span></span></div>

</div>

</div>
</div>

### pointer {#ad11200453a8ff0bf95cbaedb50dff510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirIterator::pointer =  value_type*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad11200453a8ff0bf95cbaedb50dff510">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad11200453a8ff0bf95cbaedb50dff510">pointer</a> = <a href="#a144120a41958226a725d3d2533a7c783">value_type</a>*;</span></span></div>

</div>

</div>
</div>

### reference {#a2715f06935759c6e7996c6cc26691514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirIterator::reference =  value_type&amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2715f06935759c6e7996c6cc26691514">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2715f06935759c6e7996c6cc26691514">reference</a> = <a href="#a144120a41958226a725d3d2533a7c783">value_type</a>&amp;;</span></span></div>

</div>

</div>
</div>

### value\_type {#a144120a41958226a725d3d2533a7c783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirIterator::value_type =  DirEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a144120a41958226a725d3d2533a7c783">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a144120a41958226a725d3d2533a7c783">value_type</a> = <a href="/web-doxygen/docs/api/classes/direntry">DirEntry</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### begin {#ab6c94b68ae7d5509e621425954c7fc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> it</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6c94b68ae7d5509e621425954c7fc50">170</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ab6c94b68ae7d5509e621425954c7fc50">begin</a>(<a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> it) </span><span class="doxyHighlightKeyword">noexcept</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>.</p>

</div>
</div>

### Dir {#a9c037aa57ccb12f75092ea55062c933e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/dir">Dir</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c037aa57ccb12f75092ea55062c933e">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#a9c037aa57ccb12f75092ea55062c933e">Dir</a>;</span></span></div>

</div>


<p>Reference <a href="#a9c037aa57ccb12f75092ea55062c933e">Dir</a>.</p>


<p>Referenced by <a href="#a9c037aa57ccb12f75092ea55062c933e">Dir</a>.</p>

</div>
</div>

### end {#ad0550a128905c4e07b633d437992b002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0550a128905c4e07b633d437992b002">175</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;) </span><span class="doxyHighlightKeyword">noexcept</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>.</p>

</div>
</div>

### operator!= {#acde2fab844e4f384c5d715f06f0835f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it1, const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 60 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acde2fab844e4f384c5d715f06f0835f4">165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#acde2fab844e4f384c5d715f06f0835f4">operator!=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it1.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it!=it2.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### operator== {#a9285cecfcff40959eed73e1da7d139da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it1, const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9285cecfcff40959eed73e1da7d139da">160</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#a9285cecfcff40959eed73e1da7d139da">operator==</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it1.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it == it2.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DirIterator() {#a182f1c600812106e59ee2c27aef102bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator::DirIterator (const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a182f1c600812106e59ee2c27aef102bc">104</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator::DirIterator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it) : <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>


<p>Referenced by <a href="#ab6c94b68ae7d5509e621425954c7fc50">begin</a>, <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>, <a href="#aeb4e1054c2150c4d5f159876a91266a9">DirIterator</a>, <a href="#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#acde2fab844e4f384c5d715f06f0835f4">operator!=</a>, <a href="#a21357cd7836791a40ecd6db98fa864f2">operator++</a>, <a href="#aa6af63e61d1cd8a695c70210d1200696">operator=</a>, <a href="#aa0c1406fad2fbd8ede290b7ba0874130">operator=</a> and <a href="#a9285cecfcff40959eed73e1da7d139da">operator==</a>.</p>

</div>
</div>

### DirIterator() {#aeb4e1054c2150c4d5f159876a91266a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator::DirIterator (<a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;&amp; it)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb4e1054c2150c4d5f159876a91266a9">122</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator::DirIterator</a>(<a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;&amp;it) : <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it,it.p-&gt;it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec,it.p-&gt;ec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current,it.p-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DirIterator() {#a0bee75c75ab8c043e77564196f39bff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator::DirIterator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bee75c75ab8c043e77564196f39bff7">96</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator::DirIterator</a>() : <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### DirIterator() {#a0a049e2a4e5b8b273e56b0bcbdf32cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator::DirIterator (const std::string &amp; path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a049e2a4e5b8b273e56b0bcbdf32cf4">100</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator::DirIterator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;path) : <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/diriterator/private">Private</a>&gt;(path))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DirIterator() {#a2d20623f235e252893d994957ec2a9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator::~DirIterator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d20623f235e252893d994957ec2a9f6">137</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a2d20623f235e252893d994957ec2a9f6">DirIterator::~DirIterator</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#a6956f8bf3894639348454cb62784c74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirIterator::value_type * DirIterator::operator-&gt; ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6956f8bf3894639348454cb62784c74f">154</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a144120a41958226a725d3d2533a7c783">DirIterator::value_type</a> *<a href="#a6956f8bf3894639348454cb62784c74f">DirIterator::operator-&gt;</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current.p-&gt;entry = *<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### operator\*() {#a54db35ff62b7ab4045a593b92ac8780d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirIterator::value_type &amp; DirIterator::operator* ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54db35ff62b7ab4045a593b92ac8780d">148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a144120a41958226a725d3d2533a7c783">DirIterator::value_type</a> &amp;<a href="#a54db35ff62b7ab4045a593b92ac8780d">DirIterator::operator*</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current.p-&gt;entry = *<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### operator++() {#a21357cd7836791a40ecd6db98fa864f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator DirIterator::operator++ ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21357cd7836791a40ecd6db98fa864f2">141</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> <a href="#a21357cd7836791a40ecd6db98fa864f2">DirIterator::operator++</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  result.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it = ++<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### operator=() {#aa6af63e61d1cd8a695c70210d1200696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator &amp; DirIterator::operator= (const <a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp; it)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6af63e61d1cd8a695c70210d1200696">111</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;<a href="#aa6af63e61d1cd8a695c70210d1200696">DirIterator::operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;it!=</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current = it.<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

### operator=() {#aa0c1406fad2fbd8ede290b7ba0874130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirIterator &amp; DirIterator::operator= (<a href="/web-doxygen/docs/api/classes/diriterator">DirIterator</a> &amp;&amp; it)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>, definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0c1406fad2fbd8ede290b7ba0874130">129</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;<a href="#aa6af63e61d1cd8a695c70210d1200696">DirIterator::operator=</a>(<a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> &amp;&amp;it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;it,it.p-&gt;it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;ec,it.p-&gt;ec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  std::exchange(<a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>-&gt;current,it.p-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a> and <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a9cc9594d5fab0c475a2de2db483f13a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; DirIterator::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cc9594d5fab0c475a2de2db483f13a9">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a9cc9594d5fab0c475a2de2db483f13a9">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a0bee75c75ab8c043e77564196f39bff7">DirIterator</a>, <a href="#a182f1c600812106e59ee2c27aef102bc">DirIterator</a>, <a href="#a0a049e2a4e5b8b273e56b0bcbdf32cf4">DirIterator</a>, <a href="#aeb4e1054c2150c4d5f159876a91266a9">DirIterator</a>, <a href="#acde2fab844e4f384c5d715f06f0835f4">operator!=</a>, <a href="#a54db35ff62b7ab4045a593b92ac8780d">operator*</a>, <a href="#a21357cd7836791a40ecd6db98fa864f2">operator++</a>, <a href="#a6956f8bf3894639348454cb62784c74f">operator-&gt;</a>, <a href="#aa6af63e61d1cd8a695c70210d1200696">operator=</a>, <a href="#aa0c1406fad2fbd8ede290b7ba0874130">operator=</a> and <a href="#a9285cecfcff40959eed73e1da7d139da">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dir-cpp">dir.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
