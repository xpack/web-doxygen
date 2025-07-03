---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/vhdlparser/vhdlparsertokenmanager-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `VhdlParserTokenManager.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "stdio.h"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h">JavaCC.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/tokenmanager-h">TokenManager.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparserconstants-h">VhdlParserConstants.h</a>"
#include "<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/vhdl">vhdl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-doxygen/docs/api/classes/token">Token</a> literal values and constants. <a href="/web-doxygen/docs/api/namespaces/vhdl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/vhdl/parser">vhdl::parser</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> Manager. <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001c4feea657cf8f87bdfa1ba634d903">jjCheckNAdd</a>(state)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29e4eeaebc760a0db8ff362fd5c04da">jjAddStates</a>(start, end)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3060e5c9431b27a30958ee20caf16a88">jjCheckNAddTwoStates</a>(state1, state2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d46166825cfbc7cad6c6fc6c88fa98">jjCheckNAddStates</a>(start, end)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81d8e4b132ec27d0c7b302bd166d8e9">JAVACC_CHARSTREAM</a>&nbsp;&nbsp;&nbsp;CharStream</td>
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

### JAVACC\_CHARSTREAM {#aa81d8e4b132ec27d0c7b302bd166d8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define JAVACC_CHARSTREAM&nbsp;&nbsp;&nbsp;CharStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsertokenmanager-h">VhdlParserTokenManager.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa81d8e4b132ec27d0c7b302bd166d8e9">85</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define JAVACC_CHARSTREAM CharStream</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#a117f0df3f3675897ccb4a63c63a12721">vhdl::parser::VhdlParserTokenManager::ReInit</a> and <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#a817fc78ccb9d705012d397eacb0805a0">vhdl::parser::VhdlParserTokenManager::VhdlParserTokenManager</a>.</p>

</div>
</div>

### jjAddStates {#ae29e4eeaebc760a0db8ff362fd5c04da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define jjAddStates(start, end)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">{\
   for (int x = start; x &lt;= <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>; x++) {\
      jjstateSet[jjnewStateCnt++] = jjnextStates[x];\
   } /*while (start++ != <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);*/\
}
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsertokenmanager-h">VhdlParserTokenManager.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae29e4eeaebc760a0db8ff362fd5c04da">65</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define jjAddStates(start, end)\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">{\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   for (int x = start; x &lt;= end; x++) {\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      jjstateSet[jjnewStateCnt++] = jjnextStates[x];\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   } </span><span class="doxyHighlightComment">/*while (start++ != end);*/</span><span class="doxyHighlightPreprocessor">\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">}</span></span></div>

</div>

</div>
</div>

### jjCheckNAdd {#a001c4feea657cf8f87bdfa1ba634d903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define jjCheckNAdd(state)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">{\
   if (jjrounds[state] != jjround)\
   {\
      jjstateSet[jjnewStateCnt++] = state;\
      jjrounds[state] = jjround;\
   }\
}
</div>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsertokenmanager-h">VhdlParserTokenManager.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a001c4feea657cf8f87bdfa1ba634d903">57</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define jjCheckNAdd(state)\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">{\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   if (jjrounds[state] != jjround)\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   {\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      jjstateSet[jjnewStateCnt++] = state;\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      jjrounds[state] = jjround;\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   }\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">}</span></span></div>

</div>

</div>
</div>

### jjCheckNAddStates {#ad9d46166825cfbc7cad6c6fc6c88fa98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define jjCheckNAddStates(start, end)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">{\
   for (int x = start; x &lt;= <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>; x++) {\
      <a href="#a001c4feea657cf8f87bdfa1ba634d903">jjCheckNAdd</a>(jjnextStates[x]);\
   } /*while (start++ != <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);*/\
}
</div>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsertokenmanager-h">VhdlParserTokenManager.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9d46166825cfbc7cad6c6fc6c88fa98">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define jjCheckNAddStates(start, end)\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">{\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   for (int x = start; x &lt;= end; x++) {\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      jjCheckNAdd(jjnextStates[x]);\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   } </span><span class="doxyHighlightComment">/*while (start++ != end);*/</span><span class="doxyHighlightPreprocessor">\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">}</span></span></div>

</div>

</div>
</div>

### jjCheckNAddTwoStates {#a3060e5c9431b27a30958ee20caf16a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define jjCheckNAddTwoStates(state1, state2)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">{\
   <a href="#a001c4feea657cf8f87bdfa1ba634d903">jjCheckNAdd</a>(state1);\
   <a href="#a001c4feea657cf8f87bdfa1ba634d903">jjCheckNAdd</a>(state2);\
}
</div>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsertokenmanager-h">VhdlParserTokenManager.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3060e5c9431b27a30958ee20caf16a88">71</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define jjCheckNAddTwoStates(state1, state2)\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">{\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   jjCheckNAdd(state1);\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   jjCheckNAdd(state2);\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
