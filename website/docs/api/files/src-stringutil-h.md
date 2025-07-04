---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/stringutil-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `stringutil.h` File Reference

<p>Some helper functions for std::string. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include &lt;string&gt;
#include &lt;string_view&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf36420334a61d2920340680cf71e7e">substituteInplace</a> (std::string &amp;s, std::string_view toReplace, std::string_view replaceWith)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replaces occurrences of substring <em>toReplace</em> in string <em>s</em> with string <em>replaceWith</em>. <a href="#abaf36420334a61d2920340680cf71e7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd7b0c2ab29fbcc02a4d17b39fb285b">substituteStringView</a> (std::string_view s, std::string_view toReplace, std::string_view replaceWith)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a new string where occurrences of substring <em>toReplace</em> in string <em>s</em> are replaced by string <em>replaceWith</em>. <a href="#a6bd7b0c2ab29fbcc02a4d17b39fb285b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef47e534975880014a6514745e885a99">stripWhiteSpace</a> (std::string_view s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a string view <em>s</em>, returns a new, narrower view on that string, skipping over any leading or trailing whitespace characters. <a href="#aef47e534975880014a6514745e885a99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd208e0912669ffb021565424b1bc05">addTerminalCharIfMissing</a> (std::string &amp;s, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a> (const char *data, const char(&amp;str)[N])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns TRUE iff <em>data</em> points to a substring that matches string literal <em>str</em> <a href="#a8e85550bd817a742a59bf46dce8f3b21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7c977e857cdf4c6e3a2e320a0dbdedf">literal_at</a> (std::string_view data, const char(&amp;str)[N])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns TRUE iff <em>data</em> points to a substring that matches string literal <em>str</em> <a href="#af7c977e857cdf4c6e3a2e320a0dbdedf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Some helper functions for std::string.</p>

<div class="doxySectionDef">

## Functions

### addTerminalCharIfMissing() {#a7dd208e0912669ffb021565424b1bc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addTerminalCharIfMissing (std::string &amp; s, char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7dd208e0912669ffb021565424b1bc05">84</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7dd208e0912669ffb021565424b1bc05">addTerminalCharIfMissing</a>(std::string &amp;s,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    s+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s[s.length()-1]!=c) s+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/pre-l/#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.</p>

</div>
</div>

### literal\_at() {#a8e85550bd817a742a59bf46dce8f3b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool literal_at (const char * data, const char(&amp;) str=[N])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns TRUE iff <em>data</em> points to a substring that matches string literal <em>str</em></p>

<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e85550bd817a742a59bf46dce8f3b21">98</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *data,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> (&amp;str)[N])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = N-1; </span><span class="doxyHighlightComment">// exclude 0 terminator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> data!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; data[0]==str[0] &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(data+1,str+1,len-1)==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#af64e373f75233e1c39a3086a00264e9e">computeIndent</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a3e870f07917a178b708537e85177a6d0">extractCopyDocId</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#adafbef72995b1327272b82a2b2075480">Markdown::Private::processNmdash</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a1ee465ed3ecc9e198028ac98d6536546">readSVGSize</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ae22648d9504bbec4b64a0c33260fbe4f">skipOverFileAndLineCommands</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae81df9187a70102c6f47ca6c2c5012f4">stripTrailingWhiteSpace</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.</p>

</div>
</div>

### literal\_at() {#af7c977e857cdf4c6e3a2e320a0dbdedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool literal_at (std::string_view data, const char(&amp;) str=[N])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns TRUE iff <em>data</em> points to a substring that matches string literal <em>str</em></p>

<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7c977e857cdf4c6e3a2e320a0dbdedf">106</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(std::string_view data,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> (&amp;str)[N])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = N-1; </span><span class="doxyHighlightComment">// exclude 0 terminator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> len&lt;=data.size() &amp;&amp; data[0]==str[0] &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(data.data()+1,str+1,len-1)==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>.</p>

</div>
</div>

### stripWhiteSpace() {#aef47e534975880014a6514745e885a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view stripWhiteSpace (std::string_view s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a string view <em>s</em>, returns a new, narrower view on that string, skipping over any leading or trailing whitespace characters.</p>

<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef47e534975880014a6514745e885a99">72</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> std::string_view <a href="#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> isspace = [](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl = s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sl==0 || (!isspace(s[0]) &amp;&amp; !isspace(s[sl-1]))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> start=0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=sl-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (start&lt;sl &amp;&amp; isspace(s[start])) start++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (start==sl) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.substr(0,0); </span><span class="doxyHighlightComment">// only whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;start &amp;&amp; isspace(s[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>])) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.substr(start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1-start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad5813e8f0f46839bf4f31d2f82789089">DefinitionImpl::_setDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#ad1fa14f7ebd8d6adedcac12a2fb83ae1">addValidAliasToMap</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#abc7e7b10db0467ec67569096d637bf01">endBrief</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aa09142ff1ca07603f8bb2150ce9ceab5">VhdlDocGen::getClass</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac6f2811c13f5afdc6966f8985ff9908c">handleInheritanceGraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#af8b36f180e1815648e477ea46cd1b234">FileDefImpl::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6006a1443e18366206b8485ee2d7b8a3">DefinitionImpl::operator=</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#af45d3a0f94b1a775de47c0502e3308ef">parseIncludeOptions</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ac5533bd798e00c23bb4b0532b036ea8b">DefinitionImpl::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a57049ae0a543644fa13d44472098f7ae">DefinitionMixin&lt; Base &gt;::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a56fca82d471e653da6daf3177a58a270">MemberDefImpl::setDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/definition-h/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>.</p>

</div>
</div>

### substituteInplace() {#abaf36420334a61d2920340680cf71e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void substituteInplace (std::string &amp; s, std::string_view toReplace, std::string_view replaceWith)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replaces occurrences of substring <em>toReplace</em> in string <em>s</em> with string <em>replaceWith</em>.</p>


<p>Modifies <em>s</em> in place.</p>


<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abaf36420334a61d2920340680cf71e7e">29</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abaf36420334a61d2920340680cf71e7e">substituteInplace</a>(std::string &amp;s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">                              std::string_view toReplace,std::string_view replaceWith)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string buf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> prevPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  buf.reserve(s.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((pos=s.find(toReplace, prevPos))!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">    buf.append(s, prevPos, pos - prevPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">    buf += replaceWith;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    prevPos = pos + toReplace.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  buf.append(s, prevPos, s.size() - prevPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  s.swap(buf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a14d4da410db9164a6dacdf2122220ce7">replaceAliasArguments</a>.</p>

</div>
</div>

### substituteStringView() {#a6bd7b0c2ab29fbcc02a4d17b39fb285b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string substituteStringView (std::string_view s, std::string_view toReplace, std::string_view replaceWith)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a new string where occurrences of substring <em>toReplace</em> in string <em>s</em> are replaced by string <em>replaceWith</em>.</p>

<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bd7b0c2ab29fbcc02a4d17b39fb285b">50</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> std::string <a href="#a6bd7b0c2ab29fbcc02a4d17b39fb285b">substituteStringView</a>(std::string_view s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">                              std::string_view toReplace,std::string_view replaceWith)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string buf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> prevPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  buf.reserve(s.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((pos=s.find(toReplace, prevPos))!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    buf.append(s, prevPos, pos - prevPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    buf += replaceWith;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    prevPos = pos + toReplace.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  buf.append(s, prevPos, s.size() - prevPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> buf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#af47739c31cd60617e53ac5a363514817">escapeAlias</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
