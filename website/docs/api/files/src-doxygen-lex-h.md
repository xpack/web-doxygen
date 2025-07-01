---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/doxygen-lex-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `doxygen_lex.h` File Reference



## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0586b8b0b092d02f4ba7d45abe328f2">YY_FATAL_ERROR</a>(msg)&nbsp;&nbsp;&nbsp;...</td>
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

### YY\_FATAL\_ERROR {#ac0586b8b0b092d02f4ba7d45abe328f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_FATAL_ERROR(msg)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">{                                                                    \
  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> msg1 = <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>;                                               \
  msg1 += "\n    lexical analyzer: ";                                \
  msg1 += <a href="/web-doxygen/docs/api/files/src/code-l/#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>();                                            \
  if (!static\_cast&lt;yyguts\_t\*&gt;(yyscanner)-&gt;yyextra\_r-&gt;fileName.isEmpty()) \
  {                                                                  \
    msg1 += " (for: ";                                               \
    msg1 += static\_cast&lt;yyguts\_t\*&gt;(yyscanner)-&gt;yyextra\_r-&gt;fileName;  \
    msg1 += ")";                                                     \
  }                                                                  \
  msg1 += "\n";                                                      \
  yy\_fatal\_error( <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(msg1) , yyscanner);                         \
}
</div>
</dd>
</dl>

Definition at line 21 of file <a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0586b8b0b092d02f4ba7d45abe328f2">21</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_FATAL_ERROR(msg)                                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">{                                                                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  QCString msg1 = msg;                                               \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  msg1 += "\n    lexical analyzer: ";                                \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  msg1 += getLexerFILE();                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  if (!static_cast&lt;yyguts_t*&gt;(yyscanner)-&gt;yyextra_r-&gt;fileName.isEmpty()) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  {                                                                  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    msg1 += " (for: ";                                               \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    msg1 += static_cast&lt;yyguts_t*&gt;(yyscanner)-&gt;yyextra_r-&gt;fileName;  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    msg1 += ")";                                                     \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }                                                                  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  msg1 += "\n";                                                      \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  yy_fatal_error( qPrint(msg1) , yyscanner);                         \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
