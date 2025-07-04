---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/filecodeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FileCodeParser` Class Reference

<p>Generic code parser. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class FileCodeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/fileparser-h">src/fileparser.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for code parsers. <a href="/web-doxygen/docs/api/classes/codeparserinterface/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bbf3ac1b836ae70528f1d9ecd11e6a">parseCode</a> (OutputCodeList &amp;codeOutIntf, const QCString &amp;scopeName, const QCString &amp;input, SrcLangExt lang, bool stripCodeComments, bool isExampleBlock, const QCString &amp;exampleName=QCString(), const FileDef *fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=FALSE, const MemberDef *memberDef=nullptr, bool showLineNumbers=TRUE, const Definition *searchCtx=nullptr, bool collectXRefs=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a source file or fragment with the goal to produce highlighted and cross-referenced output. <a href="#a16bbf3ac1b836ae70528f1d9ecd11e6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c12bd8adc70f0558385f6a80f18ffb7">resetCodeParserState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the state of the code parser. <a href="#a3c12bd8adc70f0558385f6a80f18ffb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Generic code parser.</p>

<p>Definition at line 22 of file <a href="/web-doxygen/docs/api/files/src/fileparser-h">fileparser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### parseCode() {#a16bbf3ac1b836ae70528f1d9ecd11e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCodeParser::parseCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, bool stripCodeComments, bool isExampleBlock, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * memberDef=nullptr, bool showLineNumbers=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * searchCtx=nullptr, bool collectXRefs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses a source file or fragment with the goal to produce highlighted and cross-referenced output.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] codeOutList</td>
<td class="doxyParamItemDescription"><p>interface for writing the result.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] scopeName</td>
<td class="doxyParamItemDescription"><p>Name of scope to which the code belongs.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] input</td>
<td class="doxyParamItemDescription"><p>Actual code in the form of a string</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] lang</td>
<td class="doxyParamItemDescription"><p>The programming language of the code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] stripCodeComments</td>
<td class="doxyParamItemDescription"><p>signals whether or not for the code block the doxygen comments should be stripped.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isExampleBlock</td>
<td class="doxyParamItemDescription"><p>TRUE iff the code is part of an example.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] exampleName</td>
<td class="doxyParamItemDescription"><p>Name of the example.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileDef</td>
<td class="doxyParamItemDescription"><p>File definition to which the code is associated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] startLine</td>
<td class="doxyParamItemDescription"><p>Starting line in case of a code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] endLine</td>
<td class="doxyParamItemDescription"><p>Ending line of the code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] inlineFragment</td>
<td class="doxyParamItemDescription"><p>Code fragment that is to be shown inline as part of the documentation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] memberDef</td>
<td class="doxyParamItemDescription"><p>Member definition to which the code is associated (non null in case of an inline fragment for a member).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] showLineNumbers</td>
<td class="doxyParamItemDescription"><p>if set to TRUE and also fileDef is not 0, line numbers will be added to the source fragment</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] searchCtx</td>
<td class="doxyParamItemDescription"><p>context under which search data has to be stored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] collectXRefs</td>
<td class="doxyParamItemDescription"><p>collect cross-reference relations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 25 of file <a href="/web-doxygen/docs/api/files/src/fileparser-h">fileparser.h</a>, definition at line 20 of file <a href="/web-doxygen/docs/api/files/src/fileparser-cpp">fileparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16bbf3ac1b836ae70528f1d9ecd11e6a">20</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;codeOutIntf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">21</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,    </span><span class="doxyHighlightComment">// scopeName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;     input,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a>,          </span><span class="doxyHighlightComment">// lang</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,                </span><span class="doxyHighlightComment">// stripCodeComments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,                </span><span class="doxyHighlightComment">// isExampleBlock</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,    </span><span class="doxyHighlightComment">// exampleName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *      fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                  startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                  endLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                 inlineFragment,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *,   </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                 showLineNumbers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *,  </span><span class="doxyHighlightComment">// searchCtx,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                 </span><span class="doxyHighlightComment">// collectXRefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = startLine!=-1 ? startLine : 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> length = input.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;length &amp;&amp; (endLine==-1 || lineNr&lt;=endLine))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;length &amp;&amp; input[j]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineStr = input.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i,j-i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    codeOutIntf.<a href="/web-doxygen/docs/api/classes/outputcodelist/#aa09941fc041983198d326b3b7cdc4795">startCodeLine</a>(lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileDef != </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; showLineNumbers)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      codeOutIntf.<a href="/web-doxygen/docs/api/classes/outputcodelist/#ad08d11446544b377ebb9a66f76e0a1ad">writeLineNumber</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),lineNr,!inlineFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lineStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) codeOutIntf.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a346e7da814676d131ff5dc6df4e2726b">codify</a>(lineStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    codeOutIntf.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a27b77a46a240ee024adafb99578ed91b">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    i=j+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a346e7da814676d131ff5dc6df4e2726b">OutputCodeList::codify</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#a27b77a46a240ee024adafb99578ed91b">OutputCodeList::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#aa09941fc041983198d326b3b7cdc4795">OutputCodeList::startCodeLine</a> and <a href="/web-doxygen/docs/api/classes/outputcodelist/#ad08d11446544b377ebb9a66f76e0a1ad">OutputCodeList::writeLineNumber</a>.</p>

</div>
</div>

### resetCodeParserState() {#a3c12bd8adc70f0558385f6a80f18ffb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCodeParser::resetCodeParserState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resets the state of the code parser.</p>


<p>Since multiple code fragments can together form a single example, an explicit function is used to reset the code parser state.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a16bbf3ac1b836ae70528f1d9ecd11e6a">parseCode()</a></p></dd>
</dl>


<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/fileparser-h">fileparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c12bd8adc70f0558385f6a80f18ffb7">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3c12bd8adc70f0558385f6a80f18ffb7">resetCodeParserState</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/fileparser-cpp">fileparser.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/fileparser-h">fileparser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
