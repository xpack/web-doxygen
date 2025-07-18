---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/datetime-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `datetime.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstdlib&gt;
#include &lt;chrono&gt;
#include &lt;memory&gt;
#include &lt;array&gt;
#include &lt;functional&gt;
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/datetime-h">datetime.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cdae8db18c51bf35a3a227df2a2d211">TMFieldAssigner</a> = std::function&lt; void(std::tm &amp;, int value) &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tm</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the filled in std::tm for the current date and time. <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a> (DateTimeType includeTime)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current date, when <span class="doxyComputerOutput">includeTime</span> is set also the time is provided. <a href="#a28a0c3252d0f0f28c0611cbc3268b003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a75ed644eb3f75d36151f9d82f862f">yearToString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current year as a string. <a href="#a76a75ed644eb3f75d36151f9d82f862f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5bcc9e65bd30e9f8bbac02209a365f">determine_weekday</a> (std::tm &amp;tm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a> (const QCString &amp;spec, std::tm &amp;dt, int &amp;format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the filled in std::tm for a given string representing a date and/or time. <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a> (const QCString &amp;format, const std::tm &amp;dt, int &amp;formatUsed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string representation for a given std::tm value that is formatted according to the pattern given by a format. <a href="#a9f06f858b1cd97d3bc7b850a600b45be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59caa72dd2172c28cdd1c7cad10e9b4">g_specFormats</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded1be4ca20e42c09d780b0bf95ee827">g_assignValues</a> = ...</td>
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

## Typedefs

### TMFieldAssigner {#a6cdae8db18c51bf35a3a227df2a2d211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TMFieldAssigner =  std::function&lt; void(std::tm &amp;,int value) &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cdae8db18c51bf35a3a227df2a2d211">90</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6cdae8db18c51bf35a3a227df2a2d211">TMFieldAssigner</a> = std::function&lt; void(std::tm &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dateTimeFromString() {#ad9d60769e8d4d67f018bc58c3e7b4e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString dateTimeFromString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; spec, std::tm &amp; dt, int &amp; format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the filled in std::tm for a given string representing a date and/or time.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] spec</td>
<td class="doxyParamItemDescription"><p>The string representation of the date and/or time Possible formats:</p>


<ul class="doxyList ">
<li>the empty string: the current date and time is returned</li>
<li><span class="doxyComputerOutput">YYYY-MM-DD HH:MM:SS</span>: the date and time are fully specified</li>
<li><span class="doxyComputerOutput">YYYY-MM-DD HH:MM</span>: the date and time without seconds</li>
<li><span class="doxyComputerOutput">YYYY-MM-DD</span>: the date without time</li>
<li><span class="doxyComputerOutput">HH:MM:SS</span>: the time with seconds but without date</li>
<li><span class="doxyComputerOutput">HH:MM</span>: the time without seconds and without date</li>
</ul></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] dt</td>
<td class="doxyParamItemDescription"><p>The corresponding datetime value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] format</td>
<td class="doxyParamItemDescription"><p>The parts that have been found in spec; a bitwise or of <span class="doxyComputerOutput">SF_Date</span>, <span class="doxyComputerOutput">SF_Time</span> and <span class="doxyComputerOutput">SF_Seconds</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An empty string if the spec has a supported format, or an error message if the format is invalid.</p></dd>
</dl>


<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">134</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;spec,std::tm &amp;dt,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for an empty spec field return the current date and time</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  dt = <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (spec.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    format = <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a> | <a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a> | <a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find a matching pattern</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string s = spec.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a> : <a href="#af59caa72dd2172c28cdd1c7cad10e9b4">g_specFormats</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>(s,m,<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>.re)) </span><span class="doxyHighlightComment">// match found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>.count; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value = std::atoi(m[i+1].str().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a> &amp;dtf = <a href="#aded1be4ca20e42c09d780b0bf95ee827">g_assignValues</a>[i+<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>.offset];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value&lt;dtf.minVal || value&gt;dtf.<a href="/web-doxygen/docs/api/structs/datetimefield/#a07c23c91e7604287b45b210c69763209">maxVal</a>) </span><span class="doxyHighlightComment">// check if the value is in the expected range</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"value for %s is %d which is outside of the value range [%d..%d]"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">              dtf.<a href="/web-doxygen/docs/api/structs/datetimefield/#a9b133ac640c6dad75d02da61871d2a04">name</a>, value, dtf.<a href="/web-doxygen/docs/api/structs/datetimefield/#aefa072e17ee530f19a1b8a3f1e2eade7">minVal</a>, dtf.<a href="/web-doxygen/docs/api/structs/datetimefield/#a07c23c91e7604287b45b210c69763209">maxVal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">        dtf.<a href="/web-doxygen/docs/api/structs/datetimefield/#a570e893b97430e96952d1d4950e1bdcd">assigner</a>(dt,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      format = <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>.format;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (format&amp;<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>) </span><span class="doxyHighlightComment">// if we have a date also determine the weekday</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#acd5bcc9e65bd30e9f8bbac02209a365f">determine_weekday</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// no matching pattern found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"invalid or non representable date/time argument"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/datetimefield/#a570e893b97430e96952d1d4950e1bdcd">DateTimeField::assigner</a>, <a href="#acd5bcc9e65bd30e9f8bbac02209a365f">determine_weekday</a>, <a href="#aded1be4ca20e42c09d780b0bf95ee827">g_assignValues</a>, <a href="#af59caa72dd2172c28cdd1c7cad10e9b4">g_specFormats</a>, <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>, <a href="/web-doxygen/docs/api/structs/datetimefield/#a07c23c91e7604287b45b210c69763209">DateTimeField::maxVal</a>, <a href="/web-doxygen/docs/api/structs/datetimefield/#aefa072e17ee530f19a1b8a3f1e2eade7">DateTimeField::minVal</a>, <a href="/web-doxygen/docs/api/structs/datetimefield/#a9b133ac640c6dad75d02da61871d2a04">DateTimeField::name</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae047ee79dc91f846eb14f7f882a17cdf">showDate</a>.</p>

</div>
</div>

### dateToString() {#a28a0c3252d0f0f28c0611cbc3268b003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString dateToString (<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fe">DateTimeType</a> includeTime)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the current date, when <span class="doxyComputerOutput">includeTime</span> is set also the time is provided.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] includeTime</td>
<td class="doxyParamItemDescription"><p>include the time in the output</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28a0c3252d0f0f28c0611cbc3268b003">63</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>(<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fe">DateTimeType</a> includeTime)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> current = <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDateTime(current.tm_year + 1900,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">                                   current.tm_mon + 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">                                   current.tm_mday,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">                                   (current.tm_wday+6)%7+1, </span><span class="doxyHighlightComment">// map: Sun=0..Sat=6 to Mon=1..Sun=7</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">                                   current.tm_hour,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">                                   current.tm_min,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">                                   current.tm_sec,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">                                   includeTime);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0c856f41b9b3199b3f034a02d7b8309e">ManGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9fcc3d0c9d7df5c8cfe5b43686e52e1a">substituteKeywords</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>.</p>

</div>
</div>

### determine\_weekday() {#acd5bcc9e65bd30e9f8bbac02209a365f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void determine_weekday (std::tm &amp; tm)</td>
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



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd5bcc9e65bd30e9f8bbac02209a365f">121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acd5bcc9e65bd30e9f8bbac02209a365f">determine_weekday</a>( std::tm&amp; tm )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> cpy = tm;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// there are some problems when the hr:min:sec are on 00:00:00 in determining the weekday</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  cpy.tm_hour = 12;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> as_time_t = std::mktime( &amp;cpy ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (as_time_t != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    cpy = *std::localtime( &amp;as_time_t ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    tm.tm_wday = cpy.tm_wday;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>.</p>

</div>
</div>

### formatDateTime() {#a9f06f858b1cd97d3bc7b850a600b45be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString formatDateTime (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; format, const std::tm &amp; dt, int &amp; formatUsed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string representation for a given std::tm value that is formatted according to the pattern given by a format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] format</td>
<td class="doxyParamItemDescription"><p>the string used for format the date and time, e.g. <span class="doxyComputerOutput">Y-m-d</span></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] dt</td>
<td class="doxyParamItemDescription"><p>the date and time value to fill in</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] formatUsed</td>
<td class="doxyParamItemDescription"><p>A bitwise OR of <span class="doxyComputerOutput">SF_Date</span>, <span class="doxyComputerOutput">SF_Time</span> and <span class="doxyComputerOutput">SF_Seconds</span> representing the the types of markers found in the format string.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f06f858b1cd97d3bc7b850a600b45be">175</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;format,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::tm &amp;dt,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;formatUsed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  formatUsed = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getYear      = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::tm &amp;dat) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dat.tm_year+1900;    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getMonth     = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::tm &amp;dat) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dat.tm_mon+1;        };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getDay       = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::tm &amp;dat) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dat.tm_mday;         };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getDayOfWeek = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::tm &amp;dat) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (dat.tm_wday+6)%7+1; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> growBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p            = format.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fmt_zero     = </span><span class="doxyHighlightStringLiteral">"%02d"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fmt_nonzero  = </span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fmt_selected = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> nc = *p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">        fmt_selected = nc==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> ? fmt_nonzero : fmt_zero; </span><span class="doxyHighlightComment">// %-H produces 1 and %H produces 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nc==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) nc=*++p; </span><span class="doxyHighlightComment">// skip over -</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (nc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">);                                                                              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'y'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,getYear(dt)%100);                              formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'Y'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,getYear(dt));                                          formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'m'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,getMonth(dt));                                 formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'b'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trMonth(getMonth(dt),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">));          formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'B'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trMonth(getMonth(dt),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">));           formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'d'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,getDay(dt));                                   formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'u'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,getDayOfWeek(dt));   </span><span class="doxyHighlightComment">/* Monday = 1 ... Sunday = 7 */</span><span class="doxyHighlight">   formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'w'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,getDayOfWeek(dt)%7); </span><span class="doxyHighlightComment">/* Sunday = 0 ... Saturday = 6 */</span><span class="doxyHighlight"> formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDayOfWeek(getDayOfWeek(dt),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">));  formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDayOfWeek(getDayOfWeek(dt),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">));   formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'H'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,dt.tm_hour);                                   formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'I'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,dt.tm_hour%12);                                formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'p'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDayPeriod(dt.tm_hour&gt;=12));                formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'M'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,dt.tm_min);                                    formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'S'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(fmt_selected,dt.tm_sec);                                    formatUsed|=<a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">            growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*(p-1)==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">            growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(nc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">        p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a3c84320a57fe98375add64ad01e9bf3b">GrowBuf::addInt</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae047ee79dc91f846eb14f7f882a17cdf">showDate</a>.</p>

</div>
</div>

### getCurrentDateTime() {#aad46a931d39d3d99fc5d2ad2ecd5e0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tm getCurrentDateTime ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the filled in std::tm for the current date and time.</p>

<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::tm <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sourceDateEpoch = <a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>(</span><span class="doxyHighlightStringLiteral">"SOURCE_DATE_EPOCH"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sourceDateEpoch.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// see https://reproducible-builds.org/specs/source-date-epoch/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    uint64_t epoch = sourceDateEpoch.<a href="/web-doxygen/docs/api/classes/qcstring/#a524e1cd9e1c24e91d57b1cb91513fa67">toUInt64</a>(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> warnedOnce=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!warnedOnce)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"Environment variable SOURCE_DATE_EPOCH does not contain a valid number; value is '{}'\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">            sourceDateEpoch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">        warnedOnce=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// use given epoch value as current 'built' time</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> epoch_start    = std::chrono::time_point&lt;std::chrono::system_clock&gt;{};</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> epoch_seconds  = std::chrono::seconds(epoch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> build_time     = epoch_start + epoch_seconds;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      std::time_t time    = std::chrono::system_clock::to_time_t(build_time);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *gmtime(&amp;time);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// return current local time</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> now = std::chrono::system_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  std::time_t time = std::chrono::system_clock::to_time_t(now);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *localtime(&amp;time);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a524e1cd9e1c24e91d57b1cb91513fa67">QCString::toUInt64</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>.</p>


<p>Referenced by <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a2996b202ffa4a28fb842837caae8fa0f">dateToRTFDateString</a>, <a href="#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a> and <a href="#a76a75ed644eb3f75d36151f9d82f862f">yearToString</a>.</p>

</div>
</div>

### yearToString() {#a76a75ed644eb3f75d36151f9d82f862f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString yearToString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the current year as a string.</p>

<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76a75ed644eb3f75d36151f9d82f862f">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a76a75ed644eb3f75d36151f9d82f862f">yearToString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> current = <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(current.tm_year+1900);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9fcc3d0c9d7df5c8cfe5b43686e52e1a">substituteKeywords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_assignValues {#aded1be4ca20e42c09d780b0bf95ee827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array g_assignValues</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_year = value-1900; }, 1900,       9999,    "year"   },
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_mon  = value-1;    },    1,         12,    "month"  },
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_mday = value;      },    1,         31,    "day"    },
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_hour = value;      },    0,         23,    "hour"   },
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_min  = value;      },    0,         59,    "minute" },
  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,int value) { tm.tm_sec  = value;      },    0,         59,    "second" }
}
</div>
</dd>
</dl>

<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// assigner,                                            minVal,     maxVal,    name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_year = value-1900; }, 1900,       9999,    </span><span class="doxyHighlightStringLiteral">"year"</span><span class="doxyHighlight">   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_mon  = value-1;    },    1,         12,    </span><span class="doxyHighlightStringLiteral">"month"</span><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_mday = value;      },    1,         31,    </span><span class="doxyHighlightStringLiteral">"day"</span><span class="doxyHighlight">    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_hour = value;      },    0,         23,    </span><span class="doxyHighlightStringLiteral">"hour"</span><span class="doxyHighlight">   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_min  = value;      },    0,         59,    </span><span class="doxyHighlightStringLiteral">"minute"</span><span class="doxyHighlight"> },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/datetimefield">DateTimeField</a>{ [](std::tm &amp;tm,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) { tm.tm_sec  = value;      },    0,         59,    </span><span class="doxyHighlightStringLiteral">"second"</span><span class="doxyHighlight"> }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>.</p>

</div>
</div>

### g\_specFormats {#af59caa72dd2172c28cdd1c7cad10e9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array g_specFormats</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R"((\d+)-(\d+)-(\d+)\s*(\d+):(\d+):(\d+))"),  6,  0,  SF_Date|<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>|<a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a> }, 
  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R"((\d+)-(\d+)-(\d+)\s*(\d+):(\d+))"),        5,  0,  SF_Date|<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>            }, 
  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R"((\d+)-(\d+)-(\d+))"),                      3,  0,  SF_Date                    }, 
  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R"((\d+):(\d+):(\d+))"),                      3,  3,  SF_Time|<a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>         }, 
  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R"((\d+):(\d+))"),                            2,  3,  SF_Time                    }  
}
</div>
</dd>
</dl>

<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/datetime-cpp">datetime.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// regular expression,                            num values, offset, format bits</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R</span><span class="doxyHighlightStringLiteral">"((\d+)-(\d+)-(\d+)\s*(\d+):(\d+):(\d+))"),  6,  0,  <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>|<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>|<a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a> }, </span><span class="doxyHighlightComment">// format 13-04-2015 12:34:56</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R</span><span class="doxyHighlightStringLiteral">"((\d+)-(\d+)-(\d+)\s*(\d+):(\d+))"),        5,  0,  <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>|<a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>            }, </span><span class="doxyHighlightComment">// format 13-04-2015 12:34</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R</span><span class="doxyHighlightStringLiteral">"((\d+)-(\d+)-(\d+))"),                      3,  0,  <a href="/web-doxygen/docs/api/files/src/datetime-h/#ac6960e6e1f68baad800350b86fed5213">SF_Date</a>                    }, </span><span class="doxyHighlightComment">// format 13-04-2015</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R</span><span class="doxyHighlightStringLiteral">"((\d+):(\d+):(\d+))"),                      3,  3,  <a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>|<a href="/web-doxygen/docs/api/files/src/datetime-h/#a30a8258aa25f9421f924eb9d140f920d">SF_Seconds</a>         }, </span><span class="doxyHighlightComment">// format 12:34:56</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/specformat">SpecFormat</a>{ std::string_view(R</span><span class="doxyHighlightStringLiteral">"((\d+):(\d+))"),                            2,  3,  <a href="/web-doxygen/docs/api/files/src/datetime-h/#adc5ba2de9d9ec975cc60a694c13148a4">SF_Time</a>                    }  </span><span class="doxyHighlightComment">// format 12:34</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
