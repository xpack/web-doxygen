---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/sqlcodeyy-state
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `sqlcodeYY_state` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct sqlcodeYY_state { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8170071f2e08cdabea9e046385265987">code</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8632bb6999de5c3ec3389f71bf57a2">inputString</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
the code fragment as text <a href="#a2e8632bb6999de5c3ec3389f71bf57a2">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada659847a96ed5365784886406361fce">inputPosition</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
read offset during parsing <a href="#ada659847a96ed5365784886406361fce">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a323dabcac14f004b7f3190498c27a">fileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f23efc42a01c1374c20e82ce29aa9ec">inputLines</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
number of line in the code fragment <a href="#a9f23efc42a01c1374c20e82ce29aa9ec">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756aa04a624850382faac05984cba884">yyLineNr</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
current line number <a href="#a756aa04a624850382faac05984cba884">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa633f352c5050b85b95aead5ddca09">insideCodeLine</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ff3617a457baf82d69ccf1e7b5ccc6">searchCtx</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d285fabdd7aab80f68504525493892">stripCodeComments</a> = true</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2960ee55db4af9fccd2c1ab9d5b793b2">exampleBlock</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d943cddbe589cc4b9ed80dad8f9c96b">exampleName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66aa69a290939edfb960744bed019f0b">classScope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf17dde82913111c4d696e4a4dd4e93a">exampleFileDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55944f06efadab77b47b64ccbb0dac9">sourceFileDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa24b7f1aeddcacc4108d43dd7e33446">currentDefinition</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396daebc48d73dda1687dcd3703d3f38">currentMemberDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e58e79a9935e2bc1bc080e4ecd18684">includeCodeFragment</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cad7f457d87dca777352aaa7d9e872">currentFontClass</a> = nullptr</td>
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


Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxySectionDef">

## Public Member Attributes

### classScope {#a66aa69a290939edfb960744bed019f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString sqlcodeYY_state::classScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66aa69a290939edfb960744bed019f0b">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>      <a href="#a66aa69a290939edfb960744bed019f0b">classScope</a>;</span></span></div>

</div>

</div>
</div>

### code {#a8170071f2e08cdabea9e046385265987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList* sqlcodeYY_state::code = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8170071f2e08cdabea9e046385265987">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> * <a href="#a8170071f2e08cdabea9e046385265987">code</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### currentDefinition {#afa24b7f1aeddcacc4108d43dd7e33446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* sqlcodeYY_state::currentDefinition = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa24b7f1aeddcacc4108d43dd7e33446">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#afa24b7f1aeddcacc4108d43dd7e33446">currentDefinition</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### currentFontClass {#a09cad7f457d87dca777352aaa7d9e872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* sqlcodeYY_state::currentFontClass = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09cad7f457d87dca777352aaa7d9e872">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">   *<a href="#a09cad7f457d87dca777352aaa7d9e872">currentFontClass</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### currentMemberDef {#a396daebc48d73dda1687dcd3703d3f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef* sqlcodeYY_state::currentMemberDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a396daebc48d73dda1687dcd3703d3f38">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>  *<a href="#a396daebc48d73dda1687dcd3703d3f38">currentMemberDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### exampleBlock {#a2960ee55db4af9fccd2c1ab9d5b793b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sqlcodeYY_state::exampleBlock = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2960ee55db4af9fccd2c1ab9d5b793b2">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">          <a href="#a2960ee55db4af9fccd2c1ab9d5b793b2">exampleBlock</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### exampleFileDef {#abf17dde82913111c4d696e4a4dd4e93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;FileDef&gt; sqlcodeYY_state::exampleFileDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf17dde82913111c4d696e4a4dd4e93a">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">     std::unique_ptr&lt;FileDef&gt; <a href="#abf17dde82913111c4d696e4a4dd4e93a">exampleFileDef</a>;</span></span></div>

</div>

</div>
</div>

### exampleName {#a7d943cddbe589cc4b9ed80dad8f9c96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString sqlcodeYY_state::exampleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d943cddbe589cc4b9ed80dad8f9c96b">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>      <a href="#a7d943cddbe589cc4b9ed80dad8f9c96b">exampleName</a>;</span></span></div>

</div>

</div>
</div>

### fileName {#a34a323dabcac14f004b7f3190498c27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString sqlcodeYY_state::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34a323dabcac14f004b7f3190498c27a">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>      <a href="#a34a323dabcac14f004b7f3190498c27a">fileName</a>;</span></span></div>

</div>

</div>
</div>

### includeCodeFragment {#a1e58e79a9935e2bc1bc080e4ecd18684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sqlcodeYY_state::includeCodeFragment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e58e79a9935e2bc1bc080e4ecd18684">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">          <a href="#a1e58e79a9935e2bc1bc080e4ecd18684">includeCodeFragment</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### inputLines {#a9f23efc42a01c1374c20e82ce29aa9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int sqlcodeYY_state::inputLines = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

number of line in the code fragment

Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f23efc42a01c1374c20e82ce29aa9ec">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">           <a href="#a9f23efc42a01c1374c20e82ce29aa9ec">inputLines</a> = 0;        </span><span class="doxyHighlightComment">//!&lt; number of line in the code fragment</span></span></div>

</div>

</div>
</div>

### inputPosition {#ada659847a96ed5365784886406361fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int sqlcodeYY_state::inputPosition = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

read offset during parsing

Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada659847a96ed5365784886406361fce">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">           <a href="#ada659847a96ed5365784886406361fce">inputPosition</a> = 0;     </span><span class="doxyHighlightComment">//!&lt; read offset during parsing</span></span></div>

</div>

</div>
</div>

### inputString {#a2e8632bb6999de5c3ec3389f71bf57a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* sqlcodeYY_state::inputString = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

the code fragment as text

Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e8632bb6999de5c3ec3389f71bf57a2">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">   *<a href="#a2e8632bb6999de5c3ec3389f71bf57a2">inputString</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; the code fragment as text</span></span></div>

</div>

</div>
</div>

### insideCodeLine {#a5fa633f352c5050b85b95aead5ddca09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sqlcodeYY_state::insideCodeLine = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa633f352c5050b85b95aead5ddca09">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">          <a href="#a5fa633f352c5050b85b95aead5ddca09">insideCodeLine</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### searchCtx {#a12ff3617a457baf82d69ccf1e7b5ccc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* sqlcodeYY_state::searchCtx = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12ff3617a457baf82d69ccf1e7b5ccc6">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a>   *<a href="#a12ff3617a457baf82d69ccf1e7b5ccc6">searchCtx</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### sourceFileDef {#aa55944f06efadab77b47b64ccbb0dac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* sqlcodeYY_state::sourceFileDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa55944f06efadab77b47b64ccbb0dac9">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>    *<a href="#aa55944f06efadab77b47b64ccbb0dac9">sourceFileDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### stripCodeComments {#af3d285fabdd7aab80f68504525493892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sqlcodeYY_state::stripCodeComments = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3d285fabdd7aab80f68504525493892">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">          <a href="#af3d285fabdd7aab80f68504525493892">stripCodeComments</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### yyLineNr {#a756aa04a624850382faac05984cba884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int sqlcodeYY_state::yyLineNr = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

current line number

Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a756aa04a624850382faac05984cba884">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">           <a href="#a756aa04a624850382faac05984cba884">yyLineNr</a> = 1;          </span><span class="doxyHighlightComment">//!&lt; current line number</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/sqlcode-l">sqlcode.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
