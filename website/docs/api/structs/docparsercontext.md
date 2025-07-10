---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/docparsercontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DocParserContext` Struct Reference

<p>Parser's context to store all global variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct DocParserContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docparser-p-h">src/docparser_p.h</a>&gt;
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6d3121e0f44479868da6c290db6766">scope</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a440e2d11196fe51c4b5bc991345d866d">context</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b98ca02af34e324862e5b5b8bbfb207">xmlComment</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a0dfd1bd35105b96a1c23a5705f269277">DocNodeStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b654ab5913a22f3c0add04642776ff">styleStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a38bb1c02fb1b32ab184eb924666d4043">DefinitionStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c83376beb60d817ba1fa8f5b0d4c5b">copyStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603ea82abcc694bf2aeb91d85378aa0d">relPath</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a860ea1d5175a1046be745f7e18c9e356">StringMultiSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0040f57941740a96566faa6d223d5bcb">retvalsFound</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a860ea1d5175a1046be745f7e18c9e356">StringMultiSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c9e8118731d26df0aaf5da3795fd4f">paramsFound</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae353d958ff093eac18151351deaebf42">memberDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa499773e2ac0458b4f616b07386e5685">isExample</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688f0551d40b6f51fb0daaa76631502b">exampleName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4ae2f6f2811b5a4a4539ebddd0ddbd">prefix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc77f516caaacac57c0ddc2ef5850a3">lang</a> = SrcLangExt::Cpp</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c9c34f67532338c9595cc7eac91bb6">includeFileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741637628985f24ccf69b051638804ca">includeFileText</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04744ff470f7989ae2cb1b3d49eb6450">includeFileLine</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00595ca383d8adbe528f151fd41f437a">includeFileShowLineNo</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00c3265540f931c1b03bd3752f70d6a">stripCodeComments</a> = true</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da54182d40bdc81e85cd29db88230b6">token</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5213ee28d100e9ad9fbd9518d2a099">lineNo</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c34f5f92f5f414033ccaa71701a879">autolinkSupport</a> = false</td>
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

<p>Parser's context to store all global variables.</p>

<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### autolinkSupport {#a87c34f5f92f5f414033ccaa71701a879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::autolinkSupport = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87c34f5f92f5f414033ccaa71701a879">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">     <a href="#a87c34f5f92f5f414033ccaa71701a879">autolinkSupport</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### context {#a440e2d11196fe51c4b5bc991345d866d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a440e2d11196fe51c4b5bc991345d866d">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a440e2d11196fe51c4b5bc991345d866d">context</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### copyStack {#a67c83376beb60d817ba1fa8f5b0d4c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionStack DocParserContext::copyStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67c83376beb60d817ba1fa8f5b0d4c5b">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a38bb1c02fb1b32ab184eb924666d4043">DefinitionStack</a> <a href="#a67c83376beb60d817ba1fa8f5b0d4c5b">copyStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>.</p>

</div>
</div>

### exampleName {#a688f0551d40b6f51fb0daaa76631502b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::exampleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a688f0551d40b6f51fb0daaa76631502b">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>     <a href="#a688f0551d40b6f51fb0daaa76631502b">exampleName</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### fileName {#a2b4c522f7f52850b1956b1b1504c4f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b4c522f7f52850b1956b1b1504c4f1b">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### hasParamCommand {#adfc69df470290ef49cf32d0e6cd83556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::hasParamCommand = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfc69df470290ef49cf32d0e6cd83556">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">         <a href="#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### hasReturnCommand {#ae20ce1c3e50ef1b4399b50f29f61607f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::hasReturnCommand = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae20ce1c3e50ef1b4399b50f29f61607f">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">         <a href="#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### includeFileLength {#a084f5a404c6d0e3af240a514a40ea028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocParserContext::includeFileLength = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a084f5a404c6d0e3af240a514a40ea028">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">       <a href="#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### includeFileLine {#a04744ff470f7989ae2cb1b3d49eb6450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocParserContext::includeFileLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04744ff470f7989ae2cb1b3d49eb6450">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">          <a href="#a04744ff470f7989ae2cb1b3d49eb6450">includeFileLine</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>.</p>

</div>
</div>

### includeFileName {#ac7c9c34f67532338c9595cc7eac91bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::includeFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7c9c34f67532338c9595cc7eac91bb6">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>     <a href="#ac7c9c34f67532338c9595cc7eac91bb6">includeFileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>.</p>

</div>
</div>

### includeFileOffset {#ad7292216a7f27bb942f5e2a29d661526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocParserContext::includeFileOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7292216a7f27bb942f5e2a29d661526">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">       <a href="#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### includeFileShowLineNo {#a00595ca383d8adbe528f151fd41f437a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::includeFileShowLineNo = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00595ca383d8adbe528f151fd41f437a">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">         <a href="#a00595ca383d8adbe528f151fd41f437a">includeFileShowLineNo</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>.</p>

</div>
</div>

### includeFileText {#a741637628985f24ccf69b051638804ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::includeFileText</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a741637628985f24ccf69b051638804ca">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>     <a href="#a741637628985f24ccf69b051638804ca">includeFileText</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### initialStyleStack {#a8e520e4b1b8b7a5e76c91b618fea071e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocStyleChangeStack DocParserContext::initialStyleStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e520e4b1b8b7a5e76c91b618fea071e">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a> <a href="#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### inSeeBlock {#a9e9561c7ec0edba0d50cdcb482942bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::inSeeBlock = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e9561c7ec0edba0d50cdcb482942bea">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### insideHtmlLink {#a88cb2bde6d7f9ded45c9d33f33b65bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::insideHtmlLink = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88cb2bde6d7f9ded45c9d33f33b65bb3">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### isExample {#aa499773e2ac0458b4f616b07386e5685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::isExample = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa499773e2ac0458b4f616b07386e5685">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">         <a href="#aa499773e2ac0458b4f616b07386e5685">isExample</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### lang {#a9fc77f516caaacac57c0ddc2ef5850a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SrcLangExt DocParserContext::lang = SrcLangExt::Cpp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9fc77f516caaacac57c0ddc2ef5850a3">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a>   <a href="#a9fc77f516caaacac57c0ddc2ef5850a3">lang</a> = SrcLangExt::Cpp;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### lineNo {#a9c5213ee28d100e9ad9fbd9518d2a099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocParserContext::lineNo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c5213ee28d100e9ad9fbd9518d2a099">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">      <a href="#a9c5213ee28d100e9ad9fbd9518d2a099">lineNo</a> = 0;</span></span></div>

</div>

</div>
</div>

### markdownSupport {#ac471382981c9338c82ac73b036d7a3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::markdownSupport = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac471382981c9338c82ac73b036d7a3ff">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">     <a href="#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### memberDef {#ae353d958ff093eac18151351deaebf42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef* DocParserContext::memberDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae353d958ff093eac18151351deaebf42">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *  <a href="#ae353d958ff093eac18151351deaebf42">memberDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### nodeStack {#a60c4b8ce9d77e0e425ea3191235ec27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeStack DocParserContext::nodeStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60c4b8ce9d77e0e425ea3191235ec27a">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a0dfd1bd35105b96a1c23a5705f269277">DocNodeStack</a> <a href="#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### paramsFound {#a60c9e8118731d26df0aaf5da3795fd4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMultiSet DocParserContext::paramsFound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60c9e8118731d26df0aaf5da3795fd4f">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a860ea1d5175a1046be745f7e18c9e356">StringMultiSet</a> <a href="#a60c9e8118731d26df0aaf5da3795fd4f">paramsFound</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### prefix {#a0c4ae2f6f2811b5a4a4539ebddd0ddbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c4ae2f6f2811b5a4a4539ebddd0ddbd">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>     <a href="#a0c4ae2f6f2811b5a4a4539ebddd0ddbd">prefix</a>;</span></span></div>

</div>

</div>
</div>

### relPath {#a603ea82abcc694bf2aeb91d85378aa0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a603ea82abcc694bf2aeb91d85378aa0d">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a603ea82abcc694bf2aeb91d85378aa0d">relPath</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### retvalsFound {#a0040f57941740a96566faa6d223d5bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMultiSet DocParserContext::retvalsFound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0040f57941740a96566faa6d223d5bcb">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a860ea1d5175a1046be745f7e18c9e356">StringMultiSet</a> <a href="#a0040f57941740a96566faa6d223d5bcb">retvalsFound</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### scope {#a6a6d3121e0f44479868da6c290db6766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* DocParserContext::scope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a6d3121e0f44479868da6c290db6766">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a6a6d3121e0f44479868da6c290db6766">scope</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.</p>

</div>
</div>

### searchUrl {#aa2bfd37ddbdec7e8751e6585cc53beb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParserContext::searchUrl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2bfd37ddbdec7e8751e6585cc53beb8">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>     <a href="#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### stripCodeComments {#ab00c3265540f931c1b03bd3752f70d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::stripCodeComments = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab00c3265540f931c1b03bd3752f70d6a">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">         <a href="#ab00c3265540f931c1b03bd3752f70d6a">stripCodeComments</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>.</p>

</div>
</div>

### styleStack {#a00b654ab5913a22f3c0add04642776ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocStyleChangeStack DocParserContext::styleStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00b654ab5913a22f3c0add04642776ff">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a> <a href="#a00b654ab5913a22f3c0add04642776ff">styleStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### token {#a8da54182d40bdc81e85cd29db88230b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenInfo* DocParserContext::token = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8da54182d40bdc81e85cd29db88230b6">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *<a href="#a8da54182d40bdc81e85cd29db88230b6">token</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">DocPara::injectToken</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### xmlComment {#a5b98ca02af34e324862e5b5b8bbfb207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParserContext::xmlComment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b98ca02af34e324862e5b5b8bbfb207">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5b98ca02af34e324862e5b5b8bbfb207">xmlComment</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
