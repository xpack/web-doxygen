---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/utf8-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `utf8.h` File Reference

<p>Various UTF8 related helper functions. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include &lt;cstdint&gt;
#include &lt;string&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a> (const std::string &amp;input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts the input string into a lower case version, also taking into account non-ASCII characters that has a lower case variant. <a href="#a90000b3876f8ff0fed72d2c31ecdfe11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a> (const std::string &amp;input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts the input string into a upper case version, also taking into account non-ASCII characters that has a upper case variant. <a href="#a2027564d4381eb6e539320ee8b2e0bcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a> (const std::string &amp;input, size_t pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the UTF8 character found at byte position pos in the input string. <a href="#ac0c19c2bb475bc6f27dbf06345c865a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a> (const std::string &amp;input, size_t pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the 32bit Unicode value matching character at byte position pos in the UTF8 encoded input. <a href="#a83a5739b379d70400986a723aefd42b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbde196779ff64a517b29179f3eaba7d">getUTF8CharNumBytes</a> (char firstByte)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bytes making up a single UTF8 character given the first byte in the sequence. <a href="#adbde196779ff64a517b29179f3eaba7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a> (TextStream &amp;t, const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes the UTF8 character pointed to by s to stream t and returns a pointer to the next character. <a href="#ae9de248ba9e19731fb682352dcbc1b3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854871065a3ba8571af77887ebf7e8af">lastUTF8CharIsMultibyte</a> (const std::string &amp;input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the last character in input is a multibyte character. <a href="#a854871065a3ba8571af77887ebf7e8af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c47f3df6f4ebf0e04e0810d01c9b56f">isUTF8CharUpperCase</a> (const std::string &amp;input, size_t pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the input string at byte position pos holds an upper case character. <a href="#a3c47f3df6f4ebf0e04e0810d01c9b56f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c217509aa52433aa63d199ef77968d5">isUTF8NonBreakableSpace</a> (const char *input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the first character pointed at by input is a non-breakable whitespace character. <a href="#a8c217509aa52433aa63d199ef77968d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562d68eff947d2e12b2b56800825e552">isUTF8PunctuationCharacter</a> (uint32_t unicode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the given Unicode character represents a punctuation character. <a href="#a562d68eff947d2e12b2b56800825e552">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Various UTF8 related helper functions.</p>


<p>See <a href="https://en.wikipedia.org/wiki/UTF-8">https://en.wikipedia.org/wiki/UTF-8</a> for details on UTF8 encoding.</p>


<div class="doxySectionDef">

## Functions

### convertUTF8ToLower() {#a90000b3876f8ff0fed72d2c31ecdfe11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string convertUTF8ToLower (const std::string &amp; input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts the input string into a lower case version, also taking into account non-ASCII characters that has a lower case variant.</p>

<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">187</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>(input,<a href="/web-doxygen/docs/api/files/src/debug-cpp/#af99cca26392cb3f3834262a20381e399">asciiToLower</a>,<a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/debug-cpp/#af99cca26392cb3f3834262a20381e399">asciiToLower</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a> and <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/searchindexinfo/#a52b5729b3bc658fa7fa77497e95213fd">SearchIndexInfo::add</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/filenamefn/#a2ebf0e60c327814650a598a75ab06e4c">FileNameFn::searchKey</a>, <a href="/web-doxygen/docs/api/structs/searchterm/#aec66f0d2f6bb7fb2905bc14546af792b">SearchTerm::termEncoded</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>.</p>

</div>
</div>

### convertUTF8ToUpper() {#a2027564d4381eb6e539320ee8b2e0bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string convertUTF8ToUpper (const std::string &amp; input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts the input string into a upper case version, also taking into account non-ASCII characters that has a upper case variant.</p>

<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a2027564d4381eb6e539320ee8b2e0bcd">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>(input,<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a>,<a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a45451c516f2c29857ee914a24f0d098a">convertUnicodeToUpper</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a> and <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a45451c516f2c29857ee914a24f0d098a">convertUnicodeToUpper</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a113ff6fe5b14585eebdcafbf2fe88cc4">QCString::upper</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>.</p>

</div>
</div>

### getUnicodeForUTF8CharAt() {#a83a5739b379d70400986a723aefd42b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getUnicodeForUTF8CharAt (const std::string &amp; input, size_t pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the 32bit Unicode value matching character at byte position pos in the UTF8 encoded input.</p>

<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a83a5739b379d70400986a723aefd42b0">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint32_t <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string charS = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(input,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(charS.c_str(),charS.length(),len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a> and <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>.</p>

</div>
</div>

### getUTF8CharAt() {#ac0c19c2bb475bc6f27dbf06345c865a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getUTF8CharAt (const std::string &amp; input, size_t pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the UTF8 character found at byte position pos in the input string.</p>


<p>The resulting string can be a multi byte sequence.</p>


<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;=pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numBytes=<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(input[pos]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;pos+numBytes) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> input.substr(pos,numBytes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/searchindexinfo/#a52b5729b3bc658fa7fa77497e95213fd">SearchIndexInfo::add</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>.</p>

</div>
</div>

### getUTF8CharNumBytes() {#adbde196779ff64a517b29179f3eaba7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t getUTF8CharNumBytes (char firstByte)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bytes making up a single UTF8 character given the first byte in the sequence.</p>

<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 23 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">23</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint8_t <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t num=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> uc = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uc&gt;=0x80u) </span><span class="doxyHighlightComment">// multibyte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xE0u)==0xC0u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">      num=2; </span><span class="doxyHighlightComment">// 110x.xxxx: 2 byte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xF0u)==0xE0u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">      num=3; </span><span class="doxyHighlightComment">// 1110.xxxx: 3 byte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xF8u)==0xF0u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      num=4; </span><span class="doxyHighlightComment">// 1111.0xxx: 4 byte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xFCu)==0xF8u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      num=5; </span><span class="doxyHighlightComment">// 1111.10xx: 5 byte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xFEu)==0xFCu)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">      num=6; </span><span class="doxyHighlightComment">// 1111.110x: 6 byte character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> num;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaffed37cb5d8467824e24fe6132ec1b6">nextUTF8CharPosition</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a> and <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>.</p>

</div>
</div>

### isUTF8CharUpperCase() {#a3c47f3df6f4ebf0e04e0810d01c9b56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUTF8CharUpperCase (const std::string &amp; input, size_t pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true iff the input string at byte position pos holds an upper case character.</p>

<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a3c47f3df6f4ebf0e04e0810d01c9b56f">218</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a3c47f3df6f4ebf0e04e0810d01c9b56f">isUTF8CharUpperCase</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;=pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// turn the UTF8 character at position pos into a unicode value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t code = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(input.c_str()+pos,input.length()-pos,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if the character can be converted to lower case, if so it was an upper case character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>(code)!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a> and <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::_setBriefDescription</a>.</p>

</div>
</div>

### isUTF8NonBreakableSpace() {#a8c217509aa52433aa63d199ef77968d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int isUTF8NonBreakableSpace (const char * input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the first character pointed at by input is a non-breakable whitespace character.</p>


<p>Returns the byte size of the character if there is match or 0 if not.</p>


<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a8c217509aa52433aa63d199ef77968d5">228</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a8c217509aa52433aa63d199ef77968d5">isUTF8NonBreakableSpace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(input[0])==0xC2 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(input[1])==0xA0) ? 2 : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>.</p>

</div>
</div>

### isUTF8PunctuationCharacter() {#a562d68eff947d2e12b2b56800825e552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUTF8PunctuationCharacter (uint32_t unicode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the given Unicode character represents a punctuation character.</p>

<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a562d68eff947d2e12b2b56800825e552">234</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a562d68eff947d2e12b2b56800825e552">isUTF8PunctuationCharacter</a>(uint32_t unicode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b = <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a13534af4c55105afe07d4590d28b3599">isPunctuationCharacter</a>(unicode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a13534af4c55105afe07d4590d28b3599">isPunctuationCharacter</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>.</p>

</div>
</div>

### lastUTF8CharIsMultibyte() {#a854871065a3ba8571af77887ebf7e8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lastUTF8CharIsMultibyte (const std::string &amp; input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true iff the last character in input is a multibyte character.</p>

<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a854871065a3ba8571af77887ebf7e8af">212</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a854871065a3ba8571af77887ebf7e8af">lastUTF8CharIsMultibyte</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// last byte is part of a multibyte UTF8 char if bit 8 is set and bit 7 is not</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !input.empty() &amp;&amp; (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(input[input.length()-1])&amp;0xC0)==0x80;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::_setBriefDescription</a>.</p>

</div>
</div>

### writeUTF8Char() {#ae9de248ba9e19731fb682352dcbc1b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * writeUTF8Char (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes the UTF8 character pointed to by s to stream t and returns a pointer to the next character.</p>

<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>, definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t len = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(*s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint8_t i=0;i&lt;len;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s[i]==0) </span><span class="doxyHighlightComment">// detect premature end of string (due to invalid UTF8 char)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      len=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  t.<a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">write</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s+len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">TextStream::write</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#a370900ffa665f2d187c9d87571de2fdf">ManCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acaccd6e77d3f7f597669a7c541b623a1">RTFCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a960b5f05edbdfd2ab749e6f1358fdfa0">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af173fc80e34a6372764c46d3cf4c7758">HtmlDocVisitor::writeObfuscatedMailAddress</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
