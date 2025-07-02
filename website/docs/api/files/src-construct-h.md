---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/construct-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `construct.h` File Reference



## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c78b6c191813bfea21abec61771bb8">ABSTRACT_BASE_CLASS</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Macro to implement rule of 5 for an abstract base class. <a href="#a51c78b6c191813bfea21abec61771bb8">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486a52ba5a3c818d903c8e6e1a176de9">DEFAULT_COPYABLE</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Macro to help implementing the rule of 5 for a default copyable &amp; movable class. <a href="#a486a52ba5a3c818d903c8e6e1a176de9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463380876083913ee3764113b803c040">NON_COPYABLE</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Macro to help implementing the rule of 5 for a non-copyable &amp; movable class. <a href="#a463380876083913ee3764113b803c040">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688296d263443dea19096ab2dc20139e">ONLY_DEFAULT_MOVABLE</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Macro to help implementing the rule of 5 for a class that can be moved but not copied. <a href="#a688296d263443dea19096ab2dc20139e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9a2a46760eaf661dda21da2d111bba">ONLY_MOVABLE_DECL</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f886aa80820b965aadfd38db5003af">DEFAULT_MOVABLE_IMPL</a>(cls)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### ABSTRACT\_BASE\_CLASS {#a51c78b6c191813bfea21abec61771bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ABSTRACT_BASE_CLASS(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Macro to implement rule of 5 for an abstract base class.

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    cls() = default;                              \
    cls(const cls &amp;) = delete;                    \
    cls &amp;operator=(const cls &amp;) = delete;         \
    cls(cls &amp;&amp;) = delete;                         \
    cls &amp;operator=(cls &amp;&amp;) = delete;              \
    virtual ~cls() = default;                     \
</div>
</dd>
</dl>

Definition at line 20 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51c78b6c191813bfea21abec61771bb8">20</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ABSTRACT_BASE_CLASS(cls)                  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">21</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls() = default;                              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(const cls &amp;) = delete;                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(const cls &amp;) = delete;         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(cls &amp;&amp;) = delete;                         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(cls &amp;&amp;) = delete;              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    virtual ~cls() = default;                     \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span></div>

</div>

</div>
</div>

### DEFAULT\_COPYABLE {#a486a52ba5a3c818d903c8e6e1a176de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFAULT_COPYABLE(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Macro to help implementing the rule of 5 for a default copyable &amp; movable class.

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    cls(const cls &amp;) = default;                   \
    cls &amp;operator=(const cls &amp;) = default;        \
    cls(cls &amp;&amp;) = default;                        \
    cls &amp;operator=(cls &amp;&amp;) = default;             \
    virtual ~cls() = default;
</div>
</dd>
</dl>

Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a486a52ba5a3c818d903c8e6e1a176de9">29</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DEFAULT_COPYABLE(cls)                     \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(const cls &amp;) = default;                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(const cls &amp;) = default;        \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(cls &amp;&amp;) = default;                        \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(cls &amp;&amp;) = default;             \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    virtual ~cls() = default;</span></span></div>

</div>

</div>
</div>

### DEFAULT\_MOVABLE\_IMPL {#a99f886aa80820b965aadfd38db5003af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFAULT_MOVABLE_IMPL(cls)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    cls::cls(cls &amp;&amp;) = default;                   \
    cls &amp;cls::operator=(cls &amp;&amp;) = default;        \
</div>
</dd>
</dl>

Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99f886aa80820b965aadfd38db5003af">56</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DEFAULT_MOVABLE_IMPL(cls)                 \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls::cls(cls &amp;&amp;) = default;                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;cls::operator=(cls &amp;&amp;) = default;        \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span></div>

</div>

</div>
</div>

### NON\_COPYABLE {#a463380876083913ee3764113b803c040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NON_COPYABLE(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Macro to help implementing the rule of 5 for a non-copyable &amp; movable class.

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    cls(const cls &amp;) = delete;                    \
    cls &amp;operator=(const cls &amp;) = delete;         \
    cls(cls &amp;&amp;) = delete;                         \
    cls &amp;operator=(cls &amp;&amp;) = delete;              \
</div>
</dd>
</dl>

Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a463380876083913ee3764113b803c040">37</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NON_COPYABLE(cls)                         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(const cls &amp;) = delete;                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(const cls &amp;) = delete;         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(cls &amp;&amp;) = delete;                         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(cls &amp;&amp;) = delete;              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span></div>

</div>

</div>
</div>

### ONLY\_DEFAULT\_MOVABLE {#a688296d263443dea19096ab2dc20139e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ONLY_DEFAULT_MOVABLE(cls)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Macro to help implementing the rule of 5 for a class that can be moved but not copied.

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    cls(const cls &amp;) = delete;                    \
    cls &amp;operator=(const cls &amp;) = delete;         \
    cls(cls &amp;&amp;) = default;                        \
    cls &amp;operator=(cls &amp;&amp;) = default;             \
</div>
</dd>
</dl>

Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a688296d263443dea19096ab2dc20139e">44</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ONLY_DEFAULT_MOVABLE(cls)                 \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(const cls &amp;) = delete;                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(const cls &amp;) = delete;         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(cls &amp;&amp;) = default;                        \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(cls &amp;&amp;) = default;             \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span></div>

</div>

</div>
</div>

### ONLY\_MOVABLE\_DECL {#acd9a2a46760eaf661dda21da2d111bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ONLY_MOVABLE_DECL(cls)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">    cls(const cls &amp;) = delete;                    \
    cls &amp;operator=(const cls &amp;) = delete;         \
    cls(cls &amp;&amp;);                                  \
    cls &amp;operator=(cls &amp;&amp;);                       \
</div>
</dd>
</dl>

Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd9a2a46760eaf661dda21da2d111bba">50</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ONLY_MOVABLE_DECL(cls)                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(const cls &amp;) = delete;                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(const cls &amp;) = delete;         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls(cls &amp;&amp;);                                  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    cls &amp;operator=(cls &amp;&amp;);                       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
