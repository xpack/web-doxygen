---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/doctokenizer-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `doctokenizer.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;memory&gt;
#include "<a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data associated with a token used by the comment block parser. <a href="/web-doxygen/docs/api/structs/tokeninfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doctokenizer">DocTokenizer</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TokenRetval { <a href="#ac5068e014aa0089764ab0968a14d15c4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae312610edfc5a0b680201b585c3643a3">TOKEN_SPECIFICATIONS</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34027d1fa2ba238a169f936abd3b6ed">RETVAL_SPECIFICATIONS</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;x = y,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;static <a href="/web-doxygen/docs/api/classes/token">Token</a> make_##x() { return <a href="/web-doxygen/docs/api/classes/token">Token</a>(TokenRetval::x); }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(x, y)&nbsp;&nbsp;&nbsp;case TokenRetval::x: result = #x; break;</td>
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

## Enumerations

### TokenRetval {#ac5068e014aa0089764ab0968a14d15c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class TokenRetval </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">RETVAL_SPECIFICATIONS<a id="ac5068e014aa0089764ab0968a14d15c4aa161a7f3dd868ca8a86430dbbb91a01c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TKSPEC(x,y) x = y,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae312610edfc5a0b680201b585c3643a3">TOKEN_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5068e014aa0089764ab0968a14d15c4aa161a7f3dd868ca8a86430dbbb91a01c">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af34027d1fa2ba238a169f936abd3b6ed">RETVAL_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef TKSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### RETVAL\_SPECIFICATIONS {#af34027d1fa2ba238a169f936abd3b6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RETVAL_SPECIFICATIONS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_OK,              0x10000)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_SimpleSec,       0x10001)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_ListItem,        0x10002)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_Section,         0x10003)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_Subsection,      0x10004)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_Subsubsection,   0x10005)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_Paragraph,       0x10006)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_SubParagraph,    0x10007)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndList,         0x10008)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndPre,          0x10009)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_DescData,        0x1000A)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_DescTitle,       0x1000B)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndDesc,         0x1000C)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_TableRow,        0x1000D)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_TableCell,       0x1000E)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_TableHCell,      0x1000F)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndTable,        0x10010)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndTableCell,    0x10011)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndTableRow,     0x10012)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_Internal,        0x10013)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_SwitchLang,      0x10014)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_CloseXml,        0x10015)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndBlockQuote,   0x10016)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_CopyDoc,         0x10017)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndInternal,     0x10018)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndParBlock,     0x10019)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_EndHtmlDetails,  0x1001A)  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(RetVal_SubSubParagraph, 0x1001B)
</div>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af34027d1fa2ba238a169f936abd3b6ed">45</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RETVAL_SPECIFICATIONS \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_OK,              0x10000)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_SimpleSec,       0x10001)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_ListItem,        0x10002)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_Section,         0x10003)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_Subsection,      0x10004)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_Subsubsection,   0x10005)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_Paragraph,       0x10006)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_SubParagraph,    0x10007)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndList,         0x10008)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndPre,          0x10009)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_DescData,        0x1000A)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_DescTitle,       0x1000B)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndDesc,         0x1000C)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_TableRow,        0x1000D)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_TableCell,       0x1000E)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_TableHCell,      0x1000F)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndTable,        0x10010)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndTableCell,    0x10011)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndTableRow,     0x10012)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_Internal,        0x10013)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_SwitchLang,      0x10014)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_CloseXml,        0x10015)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndBlockQuote,   0x10016)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_CopyDoc,         0x10017)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndInternal,     0x10018)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndParBlock,     0x10019)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_EndHtmlDetails,  0x1001A)  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(RetVal_SubSubParagraph, 0x1001B)</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>.</p>

</div>
</div>

### TKSPEC {#a089d6d3f1fdfc408ecbd116df51f58b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TKSPEC(x, y)&nbsp;&nbsp;&nbsp;x = y,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TKSPEC(x,y) x = y,</span></span></div>

</div>

</div>
</div>

### TKSPEC {#a089d6d3f1fdfc408ecbd116df51f58b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TKSPEC(x, y)&nbsp;&nbsp;&nbsp;static <a href="/web-doxygen/docs/api/classes/token">Token</a> make_##x() { return <a href="/web-doxygen/docs/api/classes/token">Token</a>(TokenRetval::x); }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TKSPEC(x,y) x = y,</span></span></div>

</div>

</div>
</div>

### TKSPEC {#a089d6d3f1fdfc408ecbd116df51f58b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TKSPEC(x, y)&nbsp;&nbsp;&nbsp;case TokenRetval::x: result = #x; break;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a089d6d3f1fdfc408ecbd116df51f58b1">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TKSPEC(x,y) x = y,</span></span></div>

</div>

</div>
</div>

### TOKEN\_SPECIFICATIONS {#ae312610edfc5a0b680201b585c3643a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TOKEN_SPECIFICATIONS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_EOF,          -1)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_NONE,          0)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_WORD,          1)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_LNKWORD,       2)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_WHITESPACE,    3)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_LISTITEM,      4)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_ENDLIST,       5)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_COMMAND_AT,    6) /*! Command starting with `@` */  \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_HTMLTAG,       7)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_SYMBOL,        8)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_NEWPARA,       9)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_RCSTAG,       10)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_URL,          11)                                   \
  <a href="#a089d6d3f1fdfc408ecbd116df51f58b1">TKSPEC</a>(TK_COMMAND_BS,   12) /*! Command starting with `\` */
</div>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae312610edfc5a0b680201b585c3643a3">29</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TOKEN_SPECIFICATIONS \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_EOF,          -1)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_NONE,          0)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_WORD,          1)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_LNKWORD,       2)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_WHITESPACE,    3)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_LISTITEM,      4)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_ENDLIST,       5)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_COMMAND_AT,    6) </span><span class="doxyHighlightComment">/*! Command starting with `@` */</span><span class="doxyHighlightPreprocessor">  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_HTMLTAG,       7)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_SYMBOL,        8)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_NEWPARA,       9)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_RCSTAG,       10)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_URL,          11)                                   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  TKSPEC(TK_COMMAND_BS,   12) </span><span class="doxyHighlightComment">/*! Command starting with `\` */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
