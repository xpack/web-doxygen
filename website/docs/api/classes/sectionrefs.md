---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/sectionrefs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SectionRefs` Class Reference

<p>class that represents a list of constant references to sections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class SectionRefs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/section-h">src/section.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a> = SectionInfoVec::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9204a780b875d8cf0964e52ba795aa14">SectionInfoVec</a> = std::vector&lt; const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cce204b4a51a49e478243581d36b1e2">find</a> (const QCString &amp;label) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916946003ecac73c064487bace9e4bde">add</a> (const SectionInfo *si)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a non-owning section reference. <a href="#a916946003ecac73c064487bace9e4bde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fa90afc34a443994d8fde828682681">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401307b74b5510b4aedf2418f3ada650">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3efa721d8017a60e0c5e8847af4c320e">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1d4cfee3aad3bf2589dd12c4febd95">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9204a780b875d8cf0964e52ba795aa14">SectionInfoVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a></td>
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

<p>class that represents a list of constant references to sections.</p>

<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a1f0027292f3e47cd2beb42004dc5bc80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SectionRefs::const_iterator =  SectionInfoVec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f0027292f3e47cd2beb42004dc5bc80">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a> = SectionInfoVec::const_iterator;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### SectionInfoVec {#a9204a780b875d8cf0964e52ba795aa14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SectionRefs::SectionInfoVec =  std::vector&lt;const SectionInfo*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9204a780b875d8cf0964e52ba795aa14">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9204a780b875d8cf0964e52ba795aa14">SectionInfoVec</a> = std::vector&lt;const SectionInfo*&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a916946003ecac73c064487bace9e4bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionRefs::add (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
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

<p>Adds a non-owning section reference.</p>

<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a916946003ecac73c064487bace9e4bde">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a916946003ecac73c064487bace9e4bde">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a>.emplace(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">label</a>()),si);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.push_back(si);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">SectionInfo::label</a>, <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>, <a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>.</p>

</div>
</div>

### begin() {#a54fa90afc34a443994d8fde828682681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator SectionRefs::begin ()</td>
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



<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54fa90afc34a443994d8fde828682681">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a> <a href="#a54fa90afc34a443994d8fde828682681">begin</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.cbegin(); }</span></span></div>

</div>


<p>Reference <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ad228018049ee398d0a544bb69756be3b">PageDefImpl::addSectionsToIndex</a>.</p>

</div>
</div>

### empty() {#a3efa721d8017a60e0c5e8847af4c320e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SectionRefs::empty ()</td>
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



<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3efa721d8017a60e0c5e8847af4c320e">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3efa721d8017a60e0c5e8847af4c320e">empty</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.empty(); }</span></span></div>

</div>


<p>Reference <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ad228018049ee398d0a544bb69756be3b">PageDefImpl::addSectionsToIndex</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>.</p>

</div>
</div>

### end() {#a401307b74b5510b4aedf2418f3ada650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator SectionRefs::end ()</td>
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



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a401307b74b5510b4aedf2418f3ada650">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1f0027292f3e47cd2beb42004dc5bc80">const_iterator</a> <a href="#a401307b74b5510b4aedf2418f3ada650">end</a>()</span><span class="doxyHighlightKeyword">   const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.cend(); }</span></span></div>

</div>


<p>Reference <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ad228018049ee398d0a544bb69756be3b">PageDefImpl::addSectionsToIndex</a>.</p>

</div>
</div>

### find() {#a5cce204b4a51a49e478243581d36b1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SectionInfo * SectionRefs::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label)</td>
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




<p>Returns a constant pointer to the section info given a section label or nullptr if no section with the given label can be found.</p>


<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5cce204b4a51a49e478243581d36b1e2">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *<a href="#a5cce204b4a51a49e478243581d36b1e2">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a>.find(label.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### size() {#a9e1d4cfee3aad3bf2589dd12c4febd95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t SectionRefs::size ()</td>
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



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e1d4cfee3aad3bf2589dd12c4febd95">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a9e1d4cfee3aad3bf2589dd12c4febd95">size</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.size(); }</span></span></div>

</div>


<p>Reference <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_entries {#a8ddc0e1f326840af1dd3f3f5d0ee4928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionInfoVec SectionRefs::m_entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9204a780b875d8cf0964e52ba795aa14">SectionInfoVec</a> <a href="#a8ddc0e1f326840af1dd3f3f5d0ee4928">m_entries</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a916946003ecac73c064487bace9e4bde">add</a>, <a href="#a54fa90afc34a443994d8fde828682681">begin</a>, <a href="#a3efa721d8017a60e0c5e8847af4c320e">empty</a>, <a href="#a401307b74b5510b4aedf2418f3ada650">end</a> and <a href="#a9e1d4cfee3aad3bf2589dd12c4febd95">size</a>.</p>

</div>
</div>

### m\_lookup {#adff3d92da24bc6d95aa96f9356743166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; std::string, const SectionInfo* &gt; SectionRefs::m_lookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adff3d92da24bc6d95aa96f9356743166">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt; std::string, const SectionInfo* &gt; <a href="#adff3d92da24bc6d95aa96f9356743166">m_lookup</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a916946003ecac73c064487bace9e4bde">add</a> and <a href="#a5cce204b4a51a49e478243581d36b1e2">find</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/section-h">section.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
