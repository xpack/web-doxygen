---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/plantumlmanager
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `PlantumlManager` Class Reference

<p>Singleton that manages plantuml relation actions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class PlantumlManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/plantuml-h">src/plantuml.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a> = std::map&lt; std::string, <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a> = std::map&lt; std::string, <a href="/web-doxygen/docs/api/structs/plantumlcontent">PlantumlContent</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OutputFormat { <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Plant UML output image formats. <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35b3023efc4c8d1e609fa220c17b59d">PlantumlManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38a83e442553a769951c724353cbe6a">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run plant UML tool for all images. <a href="#af38a83e442553a769951c724353cbe6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a> (const QCString &amp;outDirArg, const QCString &amp;fileName, const QCString &amp;content, OutputFormat format, const QCString &amp;engine, const QCString &amp;srcFile, int srcLine, bool inlineCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a PlantUML compatible file. <a href="#a536c4c6840f0660a5084d7bb1e32ff18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a> (const QCString &amp;baseName, const QCString &amp;outDir, OutputFormat format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a PlantUML file to an image. <a href="#af6f1c6249e4127996095d0086442fa0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> (const std::string &amp;key, const std::string &amp;value, const QCString &amp;outDir, OutputFormat format, const QCString &amp;puContent, const QCString &amp;srcFile, int srcLine)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/plantumlmanager">PlantumlManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae264d99d8756b63a55c341b4768ad28b">instance</a> ()</td>
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

<p>Singleton that manages plantuml relation actions.</p>

<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ContentMap {#a37056adb8bfd9b17785be907ff97a588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using PlantumlManager::ContentMap =  std::map&lt; std::string, PlantumlContent &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37056adb8bfd9b17785be907ff97a588">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a> = std::map&lt; std::string, PlantumlContent &gt;;</span></span></div>

</div>

</div>
</div>

### FilesMap {#a9628384c2454192c6a63b8a464f00829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using PlantumlManager::FilesMap =  std::map&lt; std::string, StringVector    &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9628384c2454192c6a63b8a464f00829">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a>   = std::map&lt; std::string, StringVector    &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### OutputFormat {#a73ccdfc6400a28af7d9d2f92215b9af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum PlantumlManager::OutputFormat </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Plant UML output image formats.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PUML_BITMAP<a id="a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PUML_EPS<a id="a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PUML_SVG<a id="a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73ccdfc6400a28af7d9d2f92215b9af5">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> { <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PlantumlManager() {#ae35b3023efc4c8d1e609fa220c17b59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PlantumlManager::PlantumlManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae35b3023efc4c8d1e609fa220c17b59d">163</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ae35b3023efc4c8d1e609fa220c17b59d">PlantumlManager::PlantumlManager</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#ae264d99d8756b63a55c341b4768ad28b">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### generatePlantUMLOutput() {#af6f1c6249e4127996095d0086442fa0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlantumlManager::generatePlantUMLOutput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a PlantUML file to an image.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] baseName</td>
<td class="doxyParamItemDescription"><p>the name of the generated file (as returned by <a href="#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource()</a>)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] outDir</td>
<td class="doxyParamItemDescription"><p>the directory to write the resulting image into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] format</td>
<td class="doxyParamItemDescription"><p>the image format to generate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6f1c6249e4127996095d0086442fa0f">128</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* outDir */</span><span class="doxyHighlight">,<a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgName = baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// The basename contains path, we need to strip the path from the filename in order</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// to create the image file name which should be included in the index.qhp (Qt help index file).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) </span><span class="doxyHighlightComment">// strip path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    imgName=imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(imgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a> and <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab259d2b0e06461957346bd3de5bb52e0">DocbookDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2ed6deb26c33df9ea8b4bc30734be81b">HtmlDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a92275d99afc832afc51d7e0deec3afe6">LatexDocVisitor::writePlantUMLFile</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8aaf0de986f15251aaa6221d226ab55a">RTFDocVisitor::writePlantUMLFile</a>.</p>

</div>
</div>

### run() {#af38a83e442553a769951c724353cbe6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlantumlManager::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run plant UML tool for all images.</p>

<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 315 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af38a83e442553a769951c724353cbe6a">315</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af38a83e442553a769951c724353cbe6a">PlantumlManager::run</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** PlantumlManager::run\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>(<a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>, <a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>(<a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>, <a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>(<a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>, <a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>, <a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>, <a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>, <a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>, <a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>, <a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a> and <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

### writePlantUMLSource() {#a536c4c6840f0660a5084d7bb1e32ff18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PlantumlManager::writePlantUMLSource (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDirArg, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; content, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; engine, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine, bool inlineCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a PlantUML compatible file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] outDirArg</td>
<td class="doxyParamItemDescription"><p>the output directory to write the file to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription"><p>the name of the file. If empty a name will be chosen automatically.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] content</td>
<td class="doxyParamItemDescription"><p>the contents of the PlantUML file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] format</td>
<td class="doxyParamItemDescription"><p>the image format to generate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] engine</td>
<td class="doxyParamItemDescription"><p>the plantuml engine to use.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] srcFile</td>
<td class="doxyParamItemDescription"><p>the source file resulting in the write command.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] srcLine</td>
<td class="doxyParamItemDescription"><p>the line number resulting in the write command.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] inlineCode</td>
<td class="doxyParamItemDescription"><p>the code is coming from the <span class="doxyComputerOutput">\statuml ... \enduml</span> (<span class="doxyComputerOutput">true</span>) command or from the <span class="doxyComputerOutput">\planumlfile</span> command (<span class="doxyComputerOutput">false</span>)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The name of the generated file.</p></dd>
</dl>


<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a536c4c6840f0660a5084d7bb1e32ff18">28</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDirArg,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;content,<a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;engine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineCode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> puName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir(outDirArg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> umlindex=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSource fileName: {}\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSource outDir: {}\n"</span><span class="doxyHighlight">,outDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip any trailing slashes and backslashes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((l=outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())&gt;0 &amp;&amp; (outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-1)==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> || outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-1)==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    outDir = outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(l-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// generate name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    puName = </span><span class="doxyHighlightStringLiteral">"inline_umlgraph_"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(umlindex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName = outDir+</span><span class="doxyHighlightStringLiteral">"/inline_umlgraph_"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(umlindex++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// user specified name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) baseName = baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    puName = baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(outDir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName =puName+</span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName =puName+</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName =puName+</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSourcebaseName: {}\n"</span><span class="doxyHighlight">,baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSourcebaseName puName: {}\n"</span><span class="doxyHighlight">,puName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSourcebaseName imgName: {}\n"</span><span class="doxyHighlight">,imgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inlineCode) text = </span><span class="doxyHighlightStringLiteral">"@start"</span><span class="doxyHighlight">+engine+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+imgName+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  text.<a href="/web-doxygen/docs/api/classes/qcstring/#a973167288278eae74d1d1c25313043fe">reserve</a>(text.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+content.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+100); </span><span class="doxyHighlightComment">// add room for image name and end marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = content.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> initial       = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      text+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: insideComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: insideComment=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (initial &amp;&amp; <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(p,</span><span class="doxyHighlightStringLiteral">"start"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// @start...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(c)) text+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// insert the image name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">            text+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">            text+=imgName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c) text+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideComment) initial=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    text+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inlineCode) text +=</span><span class="doxyHighlightStringLiteral">"@end"</span><span class="doxyHighlight">+engine+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("content\n====\n%s\n=====\n-&gt;\n-----\n%s\n------\n",qPrint(content),qPrint(text));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcOutDir(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(outDir,</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t pos = qcOutDir.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> generateType(qcOutDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(qcOutDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - (pos + 1)) );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSource generateType: {}\n"</span><span class="doxyHighlight">,generateType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a>(generateType.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),puName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),outDir,format,text,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** writePlantUMLSource generateType: {}\n"</span><span class="doxyHighlight">,generateType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a>, <a href="#ae264d99d8756b63a55c341b4768ad28b">instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a973167288278eae74d1d1c25313043fe">QCString::reserve</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ab9411b5e1c0b790a6427ac73dec643f2">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4f3ac1fc0fb8cb8218beb807d0a820d1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a> and <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insert() {#aa83ff077c80d8e2dc04a28e1629cff12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlantumlManager::insert (const std::string &amp; key, const std::string &amp; value, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; puContent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 373 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa83ff077c80d8e2dc04a28e1629cff12">373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa83ff077c80d8e2dc04a28e1629cff12">PlantumlManager::insert</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;value,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDir,<a href="#a73ccdfc6400a28af7d9d2f92215b9af5">OutputFormat</a> format,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;puContent,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>,0,</span><span class="doxyHighlightStringLiteral">"*** PlantumlManager::insert key:{} ,value:{}\n"</span><span class="doxyHighlight">,key,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ac3a7fb5f82f11c61008a85026460eab8">addPlantumlFiles</a>(<a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>,key,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a7411ea2df505d0f75b24fdd14da9ba47">addPlantumlContent</a>(<a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>,key,outDir,puContent,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ac3a7fb5f82f11c61008a85026460eab8">addPlantumlFiles</a>(<a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>,key,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a7411ea2df505d0f75b24fdd14da9ba47">addPlantumlContent</a>(<a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>,key,outDir,puContent,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ac3a7fb5f82f11c61008a85026460eab8">addPlantumlFiles</a>(<a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>,key,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a7411ea2df505d0f75b24fdd14da9ba47">addPlantumlContent</a>(<a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>,key,outDir,puContent,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>(<a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a7411ea2df505d0f75b24fdd14da9ba47">addPlantumlContent</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ac3a7fb5f82f11c61008a85026460eab8">addPlantumlFiles</a>, <a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>, <a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>, <a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>, <a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>, <a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>, <a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PUML_BITMAP</a>, <a href="#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PUML_EPS</a> and <a href="#a73ccdfc6400a28af7d9d2f92215b9af5a49f2c9b51c65731b8708f8c193a63ccf">PUML_SVG</a>.</p>


<p>Referenced by <a href="#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_epsPlantumlContent {#a865f02cdc1a05826e893485e9df32022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentMap PlantumlManager::m_epsPlantumlContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a865f02cdc1a05826e893485e9df32022">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a> <a href="#a865f02cdc1a05826e893485e9df32022">m_epsPlantumlContent</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

### m\_epsPlantumlFiles {#af736b55d9c30405deb9333eb840339da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilesMap PlantumlManager::m_epsPlantumlFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af736b55d9c30405deb9333eb840339da">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a>   <a href="#af736b55d9c30405deb9333eb840339da">m_epsPlantumlFiles</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

### m\_pngPlantumlContent {#a0df82d91beec8a3021e470aa2574c662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentMap PlantumlManager::m_pngPlantumlContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0df82d91beec8a3021e470aa2574c662">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a> <a href="#a0df82d91beec8a3021e470aa2574c662">m_pngPlantumlContent</a>;               </span><span class="doxyHighlightComment">// use circular queue for using multi-processor (multi threading)</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

### m\_pngPlantumlFiles {#ac86affddc4db57978e98e4ad07951bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilesMap PlantumlManager::m_pngPlantumlFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac86affddc4db57978e98e4ad07951bd0">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a>   <a href="#ac86affddc4db57978e98e4ad07951bd0">m_pngPlantumlFiles</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

### m\_svgPlantumlContent {#ac4dff5e930bca84db261f047c7801e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentMap PlantumlManager::m_svgPlantumlContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4dff5e930bca84db261f047c7801e67">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37056adb8bfd9b17785be907ff97a588">ContentMap</a> <a href="#ac4dff5e930bca84db261f047c7801e67">m_svgPlantumlContent</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

### m\_svgPlantumlFiles {#aeae4a1ea8542946832f282102993acd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilesMap PlantumlManager::m_svgPlantumlFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeae4a1ea8542946832f282102993acd7">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9628384c2454192c6a63b8a464f00829">FilesMap</a>   <a href="#aeae4a1ea8542946832f282102993acd7">m_svgPlantumlFiles</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa83ff077c80d8e2dc04a28e1629cff12">insert</a> and <a href="#af38a83e442553a769951c724353cbe6a">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#ae264d99d8756b63a55c341b4768ad28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PlantumlManager &amp; PlantumlManager::instance ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>, definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae264d99d8756b63a55c341b4768ad28b">157</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ae35b3023efc4c8d1e609fa220c17b59d">PlantumlManager</a> &amp;<a href="#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#ae35b3023efc4c8d1e609fa220c17b59d">PlantumlManager</a> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ae35b3023efc4c8d1e609fa220c17b59d">PlantumlManager</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ab9411b5e1c0b790a6427ac73dec643f2">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4f3ac1fc0fb8cb8218beb807d0a820d1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab259d2b0e06461957346bd3de5bb52e0">DocbookDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2ed6deb26c33df9ea8b4bc30734be81b">HtmlDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a92275d99afc832afc51d7e0deec3afe6">LatexDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8aaf0de986f15251aaa6221d226ab55a">RTFDocVisitor::writePlantUMLFile</a> and <a href="#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/plantuml-cpp">plantuml.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
