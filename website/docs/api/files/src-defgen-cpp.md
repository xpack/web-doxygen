---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/defgen-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `defgen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdlib.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defgen-h">defgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotclassgraph-h">dotclassgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a> (TextStream &amp;t, const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a> (const MemberDef *md, TextStream &amp;t, const Definition *def, const QCString &amp;prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a> (const ClassDef *cd, TextStream &amp;t, const MemberList *ml, const QCString &amp;kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a> (const ClassDef *cd, TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a> (const Definition *d, TextStream &amp;t, const MemberList *ml, const QCString &amp;kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a> (const NamespaceDef *nd, TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a> (const FileDef *fd, TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97966da890dd892ca2ff564528c82070">DEF_DB</a>(x)</td>
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

## Functions

### generateDEF() {#a39444ed87f324cf10eca40dca31c8bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 482 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39444ed87f324cf10eca40dca31c8bf9">482</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputDirectory = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(OUTPUT_DIRECTORY)+</span><span class="doxyHighlightStringLiteral">"/def"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> defDir(outputDirectory.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defDir.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>() &amp;&amp; !defDir.<a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">mkdir</a>(outputDirectory.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not create def directory in {}\n"</span><span class="doxyHighlight">,outputDirectory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName=outputDirectory+</span><span class="doxyHighlightStringLiteral">"/doxygen.def"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing!\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"AutoGen Definitions dummy;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;size()+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>-&gt;size()+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>-&gt;size()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>(cd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fn : *<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a>(fd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>(nd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"dummy_value = true;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a>, <a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">Dir::mkdir</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### generateDEFClassSection() {#a008f3c41fee6631ee72278082f3d1a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFClassSection (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; kind)</td>
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



Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a008f3c41fee6631ee72278082f3d1a2d">284</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd &amp;&amp; ml &amp;&amp; !ml-&gt;<a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-section = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    sec-kind = '"</span><span class="doxyHighlight"> &lt;&lt; kind &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>(md,t,cd,</span><span class="doxyHighlightStringLiteral">"sec"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  }; /* cp-section */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">MemberVector::empty</a> and <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>.

Referenced by <a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>.
</div>
</div>

### generateDEFForClass() {#a3dbc9c08f8cf61bdd6a98fce028ae320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFForClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



Definition at line 302 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">302</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - template arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - include files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + inheritance diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct sub classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + collaboration diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - list of all members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + user defined member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + standard member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed member documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)!=-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip anonymous compounds.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">isImplicitTemplateInstance</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip generated template instances.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-id     = '"</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-name   = '"</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-ref     = {\n"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-type = base;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-id   = '"</span><span class="doxyHighlight"> &lt;&lt; bcd.classDef-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-prot = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#a62c3d03ca859f9ec6c0820ed52f26b6c">to_string_lower_class</a>(bcd.prot) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-virt = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(bcd.virt) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-ref     = {\n"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-type = derived;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-id   = '"</span><span class="doxyHighlight"> &lt;&lt; bcd.classDef-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-prot = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#a62c3d03ca859f9ec6c0820ed52f26b6c">to_string_lower_class</a>(bcd.prot) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ref-virt = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(bcd.virt) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> numMembers = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ml-&gt;listType().isDetailed())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">      numMembers+=ml-&gt;size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (numMembers&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubTypes()),</span><span class="doxyHighlightStringLiteral">"public-type"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Interfaces()),</span><span class="doxyHighlightStringLiteral">"interfaces"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Services()),</span><span class="doxyHighlightStringLiteral">"services"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubMethods()),</span><span class="doxyHighlightStringLiteral">"public-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubAttribs()),</span><span class="doxyHighlightStringLiteral">"public-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubSlots()),</span><span class="doxyHighlightStringLiteral">"public-slot"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Signals()),</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::DcopMethods()),</span><span class="doxyHighlightStringLiteral">"dcop-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Properties()),</span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubStaticMethods()),</span><span class="doxyHighlightStringLiteral">"public-static-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"public-static-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProTypes()),</span><span class="doxyHighlightStringLiteral">"protected-type"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProMethods()),</span><span class="doxyHighlightStringLiteral">"protected-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProAttribs()),</span><span class="doxyHighlightStringLiteral">"protected-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProSlots()),</span><span class="doxyHighlightStringLiteral">"protected-slot"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProStaticMethods()),</span><span class="doxyHighlightStringLiteral">"protected-static-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"protected-static-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriTypes()),</span><span class="doxyHighlightStringLiteral">"private-type"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriMethods()),</span><span class="doxyHighlightStringLiteral">"private-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriAttribs()),</span><span class="doxyHighlightStringLiteral">"private-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriSlots()),</span><span class="doxyHighlightStringLiteral">"private-slot"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriStaticMethods()),</span><span class="doxyHighlightStringLiteral">"private-static-func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"private-static-attrib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Friends()),</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>(cd,t,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Related()),</span><span class="doxyHighlightStringLiteral">"related"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-filename  = '"</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-fileline  = '"</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()     &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-briefdesc = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-documentation = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> inheritanceGraph(cd,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">GraphType::Inheritance</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inheritanceGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">isTrivial</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-inheritancegraph = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    inheritanceGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#ac5d14ce11b024e3595c0bc9ed47c14aa">writeDEF</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> collaborationGraph(cd,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">GraphType::Collaboration</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!collaborationGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">isTrivial</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  cp-collaborationgraph = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    collaborationGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#ac5d14ce11b024e3595c0bc9ed47c14aa">writeDEF</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}; /* "</span><span class="doxyHighlight"> &lt;&lt;  cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">Collaboration</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">ClassDef::compoundTypeString</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">ClassDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">Inheritance</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">ClassDef::isImplicitTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">DotClassGraph::isTrivial</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to\_string\_lower</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a62c3d03ca859f9ec6c0820ed52f26b6c">to\_string\_lower\_class</a> and <a href="/web-doxygen/docs/api/classes/dotclassgraph/#ac5d14ce11b024e3595c0bc9ed47c14aa">DotClassGraph::writeDEF</a>.

Referenced by <a href="#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a>.
</div>
</div>

### generateDEFForFile() {#ae1923bdab69f09adecb356bed8d869f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFForFile (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



Definition at line 450 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1923bdab69f09adecb356bed8d869f0">450</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"file = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-id   = '"</span><span class="doxyHighlight"> &lt;&lt; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-name = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecDefineMembers()),</span><span class="doxyHighlightStringLiteral">"define"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecProtoMembers()),</span><span class="doxyHighlightStringLiteral">"prototype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecSequenceMembers()),</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecDictionaryMembers()),</span><span class="doxyHighlightStringLiteral">"dictionary"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(fd,t,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"var"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-full-name  = '"</span><span class="doxyHighlight"> &lt;&lt; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-first-line = '"</span><span class="doxyHighlight"> &lt;&lt; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()     &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-briefdesc  = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  file-documentation = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}; /* file */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">FileDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>.

Referenced by <a href="#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a>.
</div>
</div>

### generateDEFForMember() {#a55c1d02b9b69cd2fe313413575cc3d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFForMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix)</td>
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



Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55c1d02b9b69cd2fe313413575cc3d2c">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> memPrefix;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + declaration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - reimplements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - reimplementedBy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - exceptions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - const/volatile specifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source referenced by</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - include code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopeName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    scopeName=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    scopeName=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-member = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  memPrefix = </span><span class="doxyHighlightStringLiteral">"      "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  memPrefix.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>( <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  memPrefix.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>( </span><span class="doxyHighlightStringLiteral">"-mem-"</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> memType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a>:      memType=</span><span class="doxyHighlightStringLiteral">"define"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>:   <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">MemberType::Property</a>:    memType=</span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">MemberType::Event</a>:       memType=</span><span class="doxyHighlightStringLiteral">"event"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>:    memType=</span><span class="doxyHighlightStringLiteral">"variable"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">MemberType::Typedef</a>:     memType=</span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>: memType=</span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">MemberType::Interface</a>:   memType=</span><span class="doxyHighlightStringLiteral">"interface"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">MemberType::Service</a>:     memType=</span><span class="doxyHighlightStringLiteral">"service"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">MemberType::Sequence</a>:    memType=</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">MemberType::Dictionary</a>:  memType=</span><span class="doxyHighlightStringLiteral">"dictionary"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">MemberType::Function</a>:    memType=</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">;   isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">MemberType::Signal</a>:      memType=</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">;     isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">MemberType::Friend</a>:      memType=</span><span class="doxyHighlightStringLiteral">"friend"</span><span class="doxyHighlight">;     isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">MemberType::DCOP</a>:        memType=</span><span class="doxyHighlightStringLiteral">"dcop"</span><span class="doxyHighlight">;       isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">MemberType::Slot</a>:        memType=</span><span class="doxyHighlightStringLiteral">"slot"</span><span class="doxyHighlight">;       isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"kind = '"</span><span class="doxyHighlight"> &lt;&lt; memType &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id   = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"virt = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"prot = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">protection</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typeStr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span><span class="doxyHighlight"> &lt;&lt; typeStr &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"name = '"</span><span class="doxyHighlight"> &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFunc) </span><span class="doxyHighlightComment">//function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;defAl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> declAl = *<a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fcnPrefix = </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> + memPrefix + </span><span class="doxyHighlightStringLiteral">"param-"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> defIt = defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : declAl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *defArg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defIt!=defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        defArg = &amp;(*defIt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">        ++defIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"param = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.attrib.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"attributes = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,a.attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; a.type &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"declname = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArg &amp;&amp; !defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>!=a.name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"defname = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.array.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"array = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,a.array);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.defval.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"defval = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; a.defval &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      }; /*"</span><span class="doxyHighlight"> &lt;&lt; fcnPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-param */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (  md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> defPrefix = </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> + memPrefix + </span><span class="doxyHighlightStringLiteral">"def-"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"param  = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; defPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"name = '"</span><span class="doxyHighlight"> &lt;&lt; a.type &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      }; /*"</span><span class="doxyHighlight"> &lt;&lt; defPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-param */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"initializer = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: exceptions, const volatile</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>) </span><span class="doxyHighlightComment">// enum</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;emd : md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"enum = { enum-name = "</span><span class="doxyHighlight"> &lt;&lt; emd-&gt;name() &lt;&lt; </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!emd-&gt;initializer().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" enum-value = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,emd-&gt;initializer());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"desc-file = '"</span><span class="doxyHighlight"> &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"desc-line = '"</span><span class="doxyHighlight"> &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()     &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"briefdesc =    &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"documentation = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("md-&gt;getReferencesMembers()=%p\n",md-&gt;getReferencesMembers());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> refPrefix = </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> + memPrefix + </span><span class="doxyHighlightStringLiteral">"ref-"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refList = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">getReferencesMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd-&gt;getStartBodyLine()!=-1 &amp;&amp; rmd-&gt;getBodyDef())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"referenceto = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;getBodyDef()-&gt;getOutputFileBase()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">   </span><span class="doxyHighlightComment">// encoded ':' character (see util.cpp:convertNameToFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;anchor() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"line = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;getStartBodyLine() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope = rmd-&gt;getScopeString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = rmd-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; scope!=def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">        name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(scope+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"name = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n    };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refByList = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">getReferencedByMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refByList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd-&gt;getStartBodyLine()!=-1 &amp;&amp; rmd-&gt;getBodyDef())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; memPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"referencedby = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;getBodyDef()-&gt;getOutputFileBase()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">   </span><span class="doxyHighlightComment">// encoded ':' character (see util.cpp:convertNameToFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;anchor() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"line = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; rmd-&gt;getStartBodyLine() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope = rmd-&gt;getScopeString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = rmd-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; scope!=def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">        name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(scope+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; refPrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"name = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n    };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    }; /* "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-member */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">ArgumentList::begin</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">DCOP</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">Define</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">Dictionary</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">ArgumentList::end</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">Enumeration</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">MemberDef::enumFieldList</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">Event</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">Friend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">Function</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">MemberDef::getNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">Definition::getReferencedByMembers</a>, <a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">Definition::getReferencesMembers</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">MemberDef::initializer</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">Interface</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">Property</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">MemberDef::protection</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">Sequence</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">Service</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">Signal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">Slot</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to\_string\_lower</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">MemberDef::virtualness</a> and <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>.

Referenced by <a href="#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a> and <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>.
</div>
</div>

### generateDEFForNamespace() {#af7618d7d3aeddf3aae435cd00b9293e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFForNamespace (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



Definition at line 422 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7618d7d3aeddf3aae435cd00b9293e9">422</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  namespace = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ns-id   = '"</span><span class="doxyHighlight"> &lt;&lt; nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    ns-name = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(t,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecDefineMembers()),</span><span class="doxyHighlightStringLiteral">"define"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecProtoMembers()),</span><span class="doxyHighlightStringLiteral">"prototype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecSequenceMembers()),</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecDictionaryMembers()),</span><span class="doxyHighlightStringLiteral">"dictionary"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"func"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(nd,t,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"var"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  ns-filename  = '"</span><span class="doxyHighlight"> &lt;&lt; nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  ns-fileline  = '"</span><span class="doxyHighlight"> &lt;&lt; nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()     &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  ns-briefdesc = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  ns-documentation = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">NamespaceDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>.

Referenced by <a href="#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a>.
</div>
</div>

### generateDEFSection() {#adc602caedeaab8d348c752b53368cdc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateDEFSection (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; kind)</td>
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



Definition at line 406 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc602caedeaab8d348c752b53368cdc9">406</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml &amp;&amp; !ml-&gt;<a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight"> &lt;&lt; kind &lt;&lt; </span><span class="doxyHighlightStringLiteral">" = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>(md,t,d,kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">MemberVector::empty</a> and <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>.

Referenced by <a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a> and <a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>.
</div>
</div>

### writeDEFString() {#adb92a04549bb311fb043a2d4ca4a0a7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDEFString (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb92a04549bb311fb043a2d4ca4a0a7f">42</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c = *(p++)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">) t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.

Referenced by <a href="#ae1923bdab69f09adecb356bed8d869f0">generateDEFForFile</a>, <a href="#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a> and <a href="#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEF\_DB {#a97966da890dd892ca2ff564528c82070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEF_DB(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/defgen-cpp">defgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97966da890dd892ca2ff564528c82070">40</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DEF_DB(x)</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
