---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/sectionmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SectionManager` Class Reference

<p>singleton class that owns the list of all sections <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class SectionManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/section-h">src/section.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap&lt;T, Hash, KeyEqual, Map&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Container class representing a vector of objects with keys. <a href="/web-doxygen/docs/api/classes/linkedmap/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f211d31b783f347bb099b5857515e3">SectionManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0daaf46afaa86b8f17328eada12673">~SectionManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb62a940b1b5d7dda3b31a81a9df922">add</a> (const SectionInfo &amp;si)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320fc1c937898dd004caadd235e6d68a">add</a> (const QCString &amp;label, const QCString &amp;fileName, int lineNr, const QCString &amp;title, SectionType type, int level, const QCString &amp;ref=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01b0cef766ad1df71b59741da1d7d88">replace</a> (const QCString &amp;label, const QCString &amp;fileName, int lineNr, const QCString &amp;title, SectionType type, int level, const QCString &amp;ref=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/sectionmanager">SectionManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf31c2b2bad467541c924342b08773d">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns a reference to the singleton <a href="#afcf31c2b2bad467541c924342b08773d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>singleton class that owns the list of all sections</p>

<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### SectionManager() {#aa4f211d31b783f347bb099b5857515e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionManager::SectionManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<p>Referenced by <a href="#afcf31c2b2bad467541c924342b08773d">instance</a> and <a href="#adc0daaf46afaa86b8f17328eada12673">~SectionManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~SectionManager() {#adc0daaf46afaa86b8f17328eada12673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionManager::~SectionManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<p>Reference <a href="#aa4f211d31b783f347bb099b5857515e3">SectionManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#afbb62a940b1b5d7dda3b31a81a9df922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionInfo * SectionManager::add (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> &amp; si)</td>
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




<p>Add a new section given the data of an existing section. Returns a non-owning pointer to the newly added section.</p>


<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbb62a940b1b5d7dda3b31a81a9df922">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *<a href="#afbb62a940b1b5d7dda3b31a81a9df922">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> &amp;si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("SectionManager::add(%s,%s,%d,%s)\n",qPrint(si.label()),qPrint(si.fileName()),si.lineNr(),qPrint(si.title()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt;SectionInfo&gt;::add</a>(si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">label</a>(),si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#a84093d8cc48b4734f6e603de33d398d5">fileName</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">                      si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#a913ddc11cbf4d2e8433da4974c54543b">lineNr</a>(),si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">title</a>(),si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">type</a>(),si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#afbf60bb783ce4f773fbb77a59106d0db">level</a>(),si.<a href="/web-doxygen/docs/api/classes/sectioninfo/#a56019937eddafde2ba6df46dff4e1bef">ref</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a84093d8cc48b4734f6e603de33d398d5">SectionInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">SectionInfo::label</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#afbf60bb783ce4f773fbb77a59106d0db">SectionInfo::level</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a913ddc11cbf4d2e8433da4974c54543b">SectionInfo::lineNr</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a56019937eddafde2ba6df46dff4e1bef">SectionInfo::ref</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">SectionInfo::title</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">SectionInfo::type</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8111356e211d82aed6baea53cda91872">addAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a04e4220513820012d31302361cf4f24d">anonymous_namespace{tagreader.cpp}::TagFileParser::addDocAnchors</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af9360a554b5e9b817c991a39445e2b39">addSection</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a3aae8d1912d3c3491c992ea5d60fd9d5">DefinitionImpl::addSectionsToDefinition</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>.</p>

</div>
</div>

### add() {#a320fc1c937898dd004caadd235e6d68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionInfo * SectionManager::add (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type, int level, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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




<p>Add a new section Return a non-owning pointer to the newly added section</p>


<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a320fc1c937898dd004caadd235e6d68a">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *<a href="#a320fc1c937898dd004caadd235e6d68a">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("SectionManager::add(%s,%s,%d,%s)\n",qPrint(label),qPrint(fileName),lineNr,qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt;SectionInfo&gt;::add</a>(label.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),fileName,lineNr,title,type,level,ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>.</p>

</div>
</div>

### replace() {#aa01b0cef766ad1df71b59741da1d7d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionInfo * SectionManager::replace (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type, int level, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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




<p>Replace an existing section with a new one Return a non-owning pointer to the newly added section</p>


<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa01b0cef766ad1df71b59741da1d7d88">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *<a href="#aa01b0cef766ad1df71b59741da1d7d88">replace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("SectionManager::replace(%s,%s,%d,%s)\n",qPrint(label),qPrint(fileName),lineNr,qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si = <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt;SectionInfo&gt;::find</a>(label.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a7efd18a96a64ecaf750637a6e2d37259">setFileName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a3e0b6242d45e07de5babd061596d36e6">setLineNr</a>(lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ae3af1cf2a073f6019c0bde58d8a5bed9">setTitle</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a08bfd415d3da30cd7db439f3f7c7312c">setType</a>(type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#aa7e45cd1d7cd916f81e00d9be20589af">setLevel</a>(level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a562a39c90036477bea91a2e05d3919cf">setReference</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> si;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt;SectionInfo&gt;::add</a>(label.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),fileName,lineNr,title,type,level,ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/linkedmap/#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a7efd18a96a64ecaf750637a6e2d37259">SectionInfo::setFileName</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#aa7e45cd1d7cd916f81e00d9be20589af">SectionInfo::setLevel</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a3e0b6242d45e07de5babd061596d36e6">SectionInfo::setLineNr</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a562a39c90036477bea91a2e05d3919cf">SectionInfo::setReference</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#ae3af1cf2a073f6019c0bde58d8a5bed9">SectionInfo::setTitle</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#a08bfd415d3da30cd7db439f3f7c7312c">SectionInfo::setType</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8111356e211d82aed6baea53cda91872">addAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a04e4220513820012d31302361cf4f24d">anonymous_namespace{tagreader.cpp}::TagFileParser::addDocAnchors</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af9360a554b5e9b817c991a39445e2b39">addSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#afcf31c2b2bad467541c924342b08773d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionManager &amp; SectionManager::instance ()</td>
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

<p>returns a reference to the singleton</p>

<p>Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcf31c2b2bad467541c924342b08773d">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#aa4f211d31b783f347bb099b5857515e3">SectionManager</a> &amp;<a href="#afcf31c2b2bad467541c924342b08773d">instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#aa4f211d31b783f347bb099b5857515e3">SectionManager</a> sm;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> sm;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#aa4f211d31b783f347bb099b5857515e3">SectionManager</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8111356e211d82aed6baea53cda91872">addAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a04e4220513820012d31302361cf4f24d">anonymous_namespace{tagreader.cpp}::TagFileParser::addDocAnchors</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af9360a554b5e9b817c991a39445e2b39">addSection</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a3aae8d1912d3c3491c992ea5d60fd9d5">DefinitionImpl::addSectionsToDefinition</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a798729dca95209ecdc609807a653a2bf">clearAll</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a2634e192e6fb1db99bb22fb62a9e8c0f">createJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#a7dbcc0b3d8792f7eb24a5586609bd020">DocAnchor::DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a26024c34c8fc5cbe9ba0d57218e17f1f">DocHtmlCaption::DocHtmlCaption</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a0151a88e0794af12a9e7932de2d7a928">PerlModGenerator::generatePerlModForPage</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a15f08e6d7d71c59e3d83275bbef45ac5">printSectionsTree</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a4c2746ace65d9b91347502c11ccb43cf">processSection</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a653335defbae0c2b319413c2d9376458">resolveUserReferences</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a> and <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/section-h">section.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
