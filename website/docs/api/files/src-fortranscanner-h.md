---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/fortranscanner-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `fortranscanner.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparser">FortranOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Fortran language parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparserfree">FortranOutlineParserFree</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparserfixed">FortranOutlineParserFixed</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a> (const char *contents, int *hasContLine, int fixedCommentAfter)</td>
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

### prepassFixedForm() {#a3318a36567de3b1f36059e387a801863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * prepassFixedForm (const char * contents, int * hasContLine, int fixedCommentAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 1866 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3318a36567de3b1f36059e387a801863">1866</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* contents, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> *hasContLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> fixedCommentAfter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> column=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevLineLength=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevLineAmpOrExclIndex=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> prevQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> commented=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inSingle=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inDouble=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inBackslash=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> artificialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> newContentsSize = (int)strlen(contents)+3; </span><span class="doxyHighlightComment">// \000, \n (when necessary) and one spare character (to avoid reallocation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(newContentsSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> curLine = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sizCont;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  sizCont = strlen(contents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;sizCont;i++) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    column++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = contents[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (artificialComment &amp;&amp; c != </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> &amp;&amp; spaces)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j++] = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">        artificialComment = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">        skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">        skipped++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;=newContentsSize-3) { </span><span class="doxyHighlightComment">// check for spare characters, which may be eventually used below (by &amp; and '! ')</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">      newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, newContentsSize+1000);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">      newContentsSize = newContentsSize+1000;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fullCommentLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength=column;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineAmpOrExclIndex=<a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>(&amp;contents[i-prevLineLength+1], prevLineLength,prevQuote);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prevLineAmpOrExclIndex == -1) prevLineAmpOrExclIndex = column - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skipped)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">            prevLineAmpOrExclIndex = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">            skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength+=column;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">/* Even though a full comment line is not really a comment line it can be seen as one. An empty line is also seen as a comment line (small bonus) */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">            hasContLine[curLine - 1] = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">        artificialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">        fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">        column=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">        emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">        commented=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">        prevQuote = thisQuote;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">        curLine++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">           free(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=</span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">        newContentsSize = (int)strlen(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newContents[newContentsSize - 1] != </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// to be on the safe side</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, newContentsSize+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[newContentsSize] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[newContentsSize + 1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> newContents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &lt;= fixedCommentAfter) &amp;&amp; (column!=6) &amp;&amp; !commented)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// we have some special cases in respect to strings and escaped string characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">          fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">            inBackslash = !inBackslash;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inDouble)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">              inSingle = !inSingle;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inSingle) thisQuote = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inSingle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">              inDouble = !inDouble;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inDouble) thisQuote = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">        inBackslash = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fallthrough</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'C'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'c'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &lt;= fixedCommentAfter) &amp;&amp; (column!=6))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">          emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (column==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((c == </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) &amp;&amp; !inDouble &amp;&amp; !inSingle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fallthrough</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented &amp;&amp; (column &lt; 6) &amp;&amp; ((c - </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">) &gt;= 0) &amp;&amp; ((c - </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">) &lt;= 9))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// remove numbers, i.e. labels from first 5 positions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (column==6 &amp;&amp; emptyLabel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c != </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// 0 not allowed as continuation character, see f95 standard paragraph 3.3.2.3</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prevLineAmpOrExclIndex==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">            { </span><span class="doxyHighlightComment">// add &amp; just before end of previous line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* first line is not a continuation line in code, just in snippets etc. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curLine != 1) <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a>(newContents, j+1, (j+1)-6-1, </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">              j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">            { </span><span class="doxyHighlightComment">// add &amp; just before end of previous line comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* first line is not a continuation line in code, just in snippets etc. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curLine != 1) <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a>(newContents, j+1, (j+1)-6-prevLineLength+prevLineAmpOrExclIndex+skipped, </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">              skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">              j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">              hasContLine[curLine - 1] = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c; </span><span class="doxyHighlightComment">// , just handle like space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &gt; fixedCommentAfter) &amp;&amp; !commented)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// first non commented non blank character after position fixedCommentAfter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c != </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// I'm not a possible start of doxygen comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">            artificialComment = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">            spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">            skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">          emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">    free(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j==-1) </span><span class="doxyHighlightComment">// contents was empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[0] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newContents[j] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// content ended with newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, j+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// content did not end with a newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, j+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 1] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 2] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> newContents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a738fe0f13b025379789e42ee04dcc54f">checkContLines</a> and <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
