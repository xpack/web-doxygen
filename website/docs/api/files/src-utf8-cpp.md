---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/utf8-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `utf8.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstdint&gt;
#include &lt;sstream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/caseconvert-h">caseconvert.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a> (char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bytes making up a single UTF8 character given the first byte in the sequence. <a href="#aaca02fb609a02d6006c4ae5d02a20b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a> (const char *data, int numBytes) noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a> (const char *s, size_t bytesLeft, int &amp;len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d834f2d420c5a850aa095413d0d4b5">asciiToLower</a> (uint32_t code)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a> (uint32_t code)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a> (const std::string &amp;input, char(*asciiConversionFunc)(uint32_t code), const char *(*conversionFunc)(uint32_t code))</td>
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


<div class="doxySectionDef">

## Functions

### asciiToLower() {#a28d834f2d420c5a850aa095413d0d4b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char asciiToLower (uint32_t code)</td>
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



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28d834f2d420c5a850aa095413d0d4b5">142</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a28d834f2d420c5a850aa095413d0d4b5">asciiToLower</a>(uint32_t code)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> code&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; code&lt;='Z' ? static_cast&lt;char&gt;(code+</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">-</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">) : </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(code);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### asciiToUpper() {#a6f2cbdfe21c54dae5ec48e71d7009c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char asciiToUpper (uint32_t code)</td>
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



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f2cbdfe21c54dae5ec48e71d7009c4d">147</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a>(uint32_t code)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> code&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; code&lt;='z' ? static_cast&lt;char&gt;(code+</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">-</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">) : </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(code);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>.</p>

</div>
</div>

### caseConvert() {#a7cbb154918671e6150695e6ea1bbcf6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string caseConvert (const std::string &amp; input, char(*)(uint32_t code) asciiConversionFunc, const char *(*)(uint32_t code) conversionFunc)</td>
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



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cbb154918671e6150695e6ea1bbcf6e">152</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> std::string <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> (*asciiConversionFunc)(uint32_t code),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *(*conversionFunc)(uint32_t code))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t code=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  result.reserve(input.length()); </span><span class="doxyHighlightComment">// assume all ASCII characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> bytesLeft = input.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = input.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((code=<a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(p,bytesLeft,len)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (code&lt;128) </span><span class="doxyHighlightComment">// ASCII case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = asciiConversionFunc(code);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// generic case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *conv = conversionFunc(code);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (conv==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// no difference between lower and upper case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        result.append(p,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// replace the input character with the conversion result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">        result.append(conv);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    p+=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    bytesLeft-=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>.</p>


<p>Referenced by <a href="#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a> and <a href="#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>.</p>

</div>
</div>

### convertUTF8CharToUnicode() {#a62db715498978c35a035b241e6ebdafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t convertUTF8CharToUnicode (const char * s, size_t bytesLeft, int &amp; len)</td>
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



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62db715498978c35a035b241e6ebdafb">69</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> uint32_t <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> bytesLeft,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || bytesLeft==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> uc = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uc&lt;128) </span><span class="doxyHighlightComment">// ASCII case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    len=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> uc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (bytesLeft)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xFEu)==0xFCu)</span><span class="doxyHighlightComment">// 1111110X six bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">        len=6;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 5:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xFCu)==0xF8u) </span><span class="doxyHighlightComment">// 111110XX five bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">        len=5;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 4:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xF8u)==0xF0u) </span><span class="doxyHighlightComment">// 11110XXX four bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        len=4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xF0u)==0xE0u) </span><span class="doxyHighlightComment">// 1110XXXX three bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">        len=3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((uc&amp;0xE0u)==0xC0u) </span><span class="doxyHighlightComment">// 110XXXXX two bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        len=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>(s,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        len=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> uc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>.</p>


<p>Referenced by <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>, <a href="#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a> and <a href="#a3c47f3df6f4ebf0e04e0810d01c9b56f">isUTF8CharUpperCase</a>.</p>

</div>
</div>

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

<p>Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90000b3876f8ff0fed72d2c31ecdfe11">187</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>(input,<a href="/web-doxygen/docs/api/files/src/debug-cpp/#af99cca26392cb3f3834262a20381e399">asciiToLower</a>,<a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/debug-cpp/#af99cca26392cb3f3834262a20381e399">asciiToLower</a>, <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a> and <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>.</p>


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

<p>Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2027564d4381eb6e539320ee8b2e0bcd">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a>(input,<a href="#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a>,<a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a45451c516f2c29857ee914a24f0d098a">convertUnicodeToUpper</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a6f2cbdfe21c54dae5ec48e71d7009c4d">asciiToUpper</a>, <a href="#a7cbb154918671e6150695e6ea1bbcf6e">caseConvert</a> and <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a45451c516f2c29857ee914a24f0d098a">convertUnicodeToUpper</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a113ff6fe5b14585eebdcafbf2fe88cc4">QCString::upper</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>.</p>

</div>
</div>

### decode\_utf8() {#a623576f190ae0899718fedadfd1342a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t decode_utf8 (const char * data, int numBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Decodes a given input of utf8 data to a unicode code point given the number of bytes it's made of</p>


<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a623576f190ae0899718fedadfd1342a8">55</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> uint32_t <a href="#a623576f190ae0899718fedadfd1342a8">decode_utf8</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* data , </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numBytes ) </span><span class="doxyHighlightKeyword">noexcept</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t cp = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*data);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (numBytes&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    cp &amp;= 127 &gt;&gt; numBytes; </span><span class="doxyHighlightComment">// Mask out the header bits</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=1 ; i&lt;numBytes ; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      cp = (cp&lt;&lt;6) | (static_cast&lt;unsigned char&gt;(data[i])&amp;0x3F);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>.</p>

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

<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83a5739b379d70400986a723aefd42b0">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint32_t <a href="#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string charS = <a href="#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(input,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(charS.c_str(),charS.length(),len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a> and <a href="#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>.</p>


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


<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0c19c2bb475bc6f27dbf06345c865a3">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;=pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numBytes=<a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(input[pos]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;pos+numBytes) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> input.substr(pos,numBytes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/searchindexinfo/#a52b5729b3bc658fa7fa77497e95213fd">SearchIndexInfo::add</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>.</p>

</div>
</div>

### getUTF8CharNumBytes() {#aaca02fb609a02d6006c4ae5d02a20b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t getUTF8CharNumBytes (char c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bytes making up a single UTF8 character given the first byte in the sequence.</p>

<p>Definition at line 23 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaca02fb609a02d6006c4ae5d02a20b9b">23</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint8_t <a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
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


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaffed37cb5d8467824e24fe6132ec1b6">nextUTF8CharPosition</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a> and <a href="#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>.</p>

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

<p>Definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c47f3df6f4ebf0e04e0810d01c9b56f">218</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3c47f3df6f4ebf0e04e0810d01c9b56f">isUTF8CharUpperCase</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.length()&lt;=pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// turn the UTF8 character at position pos into a unicode value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t code = <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>(input.c_str()+pos,input.length()-pos,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if the character can be converted to lower case, if so it was an upper case character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a>(code)!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/caseconvert-h/#a639df87d0846c7b6b01b931a51f06df2">convertUnicodeToLower</a> and <a href="#a62db715498978c35a035b241e6ebdafb">convertUTF8CharToUnicode</a>.</p>


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


<p>Definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c217509aa52433aa63d199ef77968d5">228</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8c217509aa52433aa63d199ef77968d5">isUTF8NonBreakableSpace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *input)</span></span></div>
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

<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a562d68eff947d2e12b2b56800825e552">234</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a562d68eff947d2e12b2b56800825e552">isUTF8PunctuationCharacter</a>(uint32_t unicode)</span></span></div>
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

<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a854871065a3ba8571af77887ebf7e8af">212</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a854871065a3ba8571af77887ebf7e8af">lastUTF8CharIsMultibyte</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input)</span></span></div>
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

<p>Definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/utf8-cpp">utf8.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9de248ba9e19731fb682352dcbc1b3c">197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t len = <a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(*s);</span></span></div>
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


<p>References <a href="#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">TextStream::write</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#a370900ffa665f2d187c9d87571de2fdf">ManCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acaccd6e77d3f7f597669a7c541b623a1">RTFCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a960b5f05edbdfd2ab749e6f1358fdfa0">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af173fc80e34a6372764c46d3cf4c7758">HtmlDocVisitor::writeObfuscatedMailAddress</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
