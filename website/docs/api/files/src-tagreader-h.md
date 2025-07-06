---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/tagreader-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `tagreader.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d32e92baab895d320ba31f78751673">parseTagFile</a> (const std::shared_ptr&lt; Entry &gt; &amp;root, const char *fullPathName)</td>
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

### parseTagFile() {#a15d32e92baab895d320ba31f78751673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseTagFile (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, const char * fullPathName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-doxygen/docs/api/files/src/tagreader-h">tagreader.h</a>, definition at line 1864 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">1864</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fullName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a43f4ea41f01f767ade7898b8d69d0f43">TagFileParser</a> tagFileParser(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inputStr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> handlers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// connect the generic events handlers of the XML parser to the specific handlers of the tagFileParser object</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#ae666b94024ae82743cc7b8ae6445e684">startDocument</a> = [&amp;tagFileParser]()                                                              { tagFileParser.startDocument(); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a>  = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrs)  { tagFileParser.startElement(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name),attrs); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">endElement</a>    = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name)                                       { tagFileParser.endElement(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a895a088f5352bced5cf6a998da7fc06a">characters</a>    = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;chars)                                      { tagFileParser.characters(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(chars)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">error</a>         = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>) { tagFileParser.error(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(fileName),lineNr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> parser(handlers);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.setDocumentLocator(&amp;parser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  parser.<a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">parse</a>(fullName,inputStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Entering"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,fullName); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Finished"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,fullName); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.buildLists(root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.addIncludes();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">    tagFileParser.dump();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a895a088f5352bced5cf6a998da7fc06a">XMLHandlers::characters</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">XMLHandlers::endElement</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">XMLHandlers::error</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">XMLParser::parse</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ae666b94024ae82743cc7b8ae6445e684">XMLHandlers::startDocument</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">XMLHandlers::startElement</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a43f4ea41f01f767ade7898b8d69d0f43">anonymous{tagreader.cpp}::TagFileParser::TagFileParser</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
