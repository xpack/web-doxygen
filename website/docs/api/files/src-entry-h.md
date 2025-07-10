---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/entry-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `entry.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;sstream&gt;
#include &lt;functional&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "configvalues.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/commandoverrides">CommandOverrides</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/baseinfo">BaseInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class stores information about an inheritance relation. <a href="/web-doxygen/docs/api/structs/baseinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/taginfo">TagInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This struct is used to capture the tag file information for an <a href="/web-doxygen/docs/api/classes/entry">Entry</a>. <a href="/web-doxygen/docs/api/structs/taginfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/entry">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an unstructured piece of information, about an entity found in the sources. <a href="/web-doxygen/docs/api/classes/entry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &gt; <a href="#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7a858993a3764387f7a9d7a398e39c">COMMAND_OVERRIDES</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(type, store_type, bits, name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(type, store_type, bits, name)&nbsp;&nbsp;&nbsp;...</td>
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

### EntryList {#abd47085ad2ebd874e6b5d92f426e31b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt; std::shared_ptr&lt;Entry&gt; &gt; EntryList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd47085ad2ebd874e6b5d92f426e31b1">269</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> std::vector&lt; std::shared_ptr&lt;Entry&gt; &gt; <a href="#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### COMMAND\_OVERRIDES {#a9b7a858993a3764387f7a9d7a398e39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMMAND_OVERRIDES&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, callGraph            ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, callerGraph          ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, referencedByRelation ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, referencesRelation   ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, inlineSource         ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, includeGraph         ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, includedByGraph      ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, directoryGraph       ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, collaborationGraph   ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, groupGraph           ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(bool,          bool, 1, enumValues           ) \
  <a href="#a39e0f3964269b8ff50bc8c841e2dd073">OVERRIDE_ENTRY</a>(CLASS_GRAPH_t, int,  3, inheritanceGraph     )
</div>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b7a858993a3764387f7a9d7a398e39c">37</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define COMMAND_OVERRIDES                                       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, callGraph            ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, callerGraph          ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, referencedByRelation ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, referencesRelation   ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, inlineSource         ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, includeGraph         ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, includedByGraph      ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, directoryGraph       ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, collaborationGraph   ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, groupGraph           ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(bool,          bool, 1, enumValues           ) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  OVERRIDE_ENTRY(CLASS_GRAPH_t, int,  3, inheritanceGraph     )</span></span></div>

</div>

</div>
</div>

### OVERRIDE\_ENTRY {#a39e0f3964269b8ff50bc8c841e2dd073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OVERRIDE_ENTRY(type, store_type, bits, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    store_type m_##name          : bits;       \
    bool m_##name##ExplicitlySet : 1;
</div>
</dd>
</dl>

<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39e0f3964269b8ff50bc8c841e2dd073">54</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define OVERRIDE_ENTRY(type,store_type,bits,name)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    store_type m_##name          : bits;       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    bool m_##name##ExplicitlySet : 1;</span></span></div>

</div>

</div>
</div>

### OVERRIDE\_ENTRY {#a39e0f3964269b8ff50bc8c841e2dd073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OVERRIDE_ENTRY(type, store_type, bits, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    void override_##name(type value) {                         \
      m_##name = to_store_type(value);                         \
      m_##name##ExplicitlySet = true;                          \
      /* printf("overrule_%s(%d) isSet=%d\n",#name,value,m_##name##ExplicitlySet); */ \
    }                                                          \
    void apply_##name(std::function&lt;void(type)&gt; func) const {  \
      /* printf("apply_%s(%d) isSet=%d\n",#name,m_##name,m_##name##ExplicitlySet); */ \
      if (m_##name##ExplicitlySet) func(from_store_type(m_##name)); \
    }
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39e0f3964269b8ff50bc8c841e2dd073">54</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define OVERRIDE_ENTRY(type,store_type,bits,name)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    store_type m_##name          : bits;       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    bool m_##name##ExplicitlySet : 1;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
