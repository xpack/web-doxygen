---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/namespacelinkedrefmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NamespaceLinkedRefMap` Class Reference



## Declaration

<div class="doxyDeclaration">
class NamespaceLinkedRefMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/namespacedef-h">src/namespacedef.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap&lt;T, Hash, KeyEqual, Map&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Container class representing a vector of objects with keys. <a href="/web-doxygen/docs/api/classes/linkedrefmap/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9013801184ee3d3a93868770656ba2">writeDeclaration</a> (OutputList &amp;ol, const QCString &amp;title, bool isConstantGroup=false, bool localName=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e6abc4211a4481ccd467d63d04a1eb">declVisible</a> (bool isContantGroup) const</td>
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


<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### declVisible() {#ad8e6abc4211a4481ccd467d63d04a1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NamespaceLinkedRefMap::declVisible (bool isContantGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1348 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8e6abc4211a4481ccd467d63d04a1eb">1348</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad8e6abc4211a4481ccd467d63d04a1eb">NamespaceLinkedRefMap::declVisible</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isConstantGroup)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;isLinkable() &amp;&amp; nd-&gt;hasDocumentation())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = nd-&gt;getLanguage();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (SrcLangExt::IDL==lang)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isConstantGroup == nd-&gt;isConstantGroup())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">          found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isConstantGroup) </span><span class="doxyHighlightComment">// ensure we only get extra section in IDL</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;isConstantGroup())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Internal inconsistency: constant group but not IDL?\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">        found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>.</p>


<p>Referenced by <a href="#a5d9013801184ee3d3a93868770656ba2">writeDeclaration</a>.</p>

</div>
</div>

### writeDeclaration() {#a5d9013801184ee3d3a93868770656ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamespaceLinkedRefMap::writeDeclaration (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, bool isConstantGroup=false, bool localName=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1378 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d9013801184ee3d3a93868770656ba2">1378</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> isConstantGroup,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> localName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// no namespaces in the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_VHDL)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad8e6abc4211a4481ccd467d63d04a1eb">declVisible</a>(isConstantGroup)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write list of namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">startMemberHeader</a>(isConstantGroup ? </span><span class="doxyHighlightStringLiteral">"constantgroups"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"namespaces"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool javaOpt    = Config_getBool(OPTIMIZE_OUTPUT_JAVA);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool fortranOpt = Config_getBool(OPTIMIZE_FOR_FORTRAN);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">endMemberHeader</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">startMemberList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;isLinkable() &amp;&amp; nd-&gt;hasDocumentation())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = nd-&gt;getLanguage();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::IDL &amp;&amp; (isConstantGroup != nd-&gt;isConstantGroup()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// will be output in another pass, see layout_default.xml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a09a4062cfac0ed8f9d3dec4cd42f1aa7">startMemberDeclaration</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = localName ? nd-&gt;localName() : nd-&gt;displayName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anc = nd-&gt;anchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (anc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) anc=name; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> anc.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(name+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">startMemberItem</a>(anc,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ct = nd-&gt;compoundTypeString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(ct);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(nd-&gt;getReference(),nd-&gt;getOutputFileBase(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">endMemberItem</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nd-&gt;briefDescription().isEmpty() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(BRIEF_MEMBER_DESC))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">startMemberDescription</a>(nd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>(nd-&gt;briefFile(),nd-&gt;briefLine(),nd,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,nd-&gt;briefDescription(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">endMemberDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acd8c06dad427743e4bf81f94bd450e6f">endMemberDeclaration</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">endMemberList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad8e6abc4211a4481ccd467d63d04a1eb">declVisible</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">LinkedRefMap&lt; const NamespaceDef &gt;::empty</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acd8c06dad427743e4bf81f94bd450e6f">OutputList::endMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">OutputList::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">OutputList::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">OutputList::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">OutputList::endMemberList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::Normal</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a09a4062cfac0ed8f9d3dec4cd42f1aa7">OutputList::startMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">OutputList::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">OutputList::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">OutputList::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">OutputList::startMemberList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
