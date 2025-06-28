---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reg/ex/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Class Reference

<p><a href="/web-doxygen/docs/api/classes/reg/ex/private">Private</a> members of a regular expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class reg::Ex::Private { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f746ba480aec926ff3b83fdebb197a">Private</a> (std::string_view pat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates the private part. <a href="#aa3f746ba480aec926ff3b83fdebb197a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae763e5ab5231eae1133e68093c49be">compile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compiles a regular expression passed as a string into a stream of tokens that can be used for efficient searching. <a href="#a5ae763e5ab5231eae1133e68093c49be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a> (size_t tokenPos, size_t tokenLen, std::string_view str, Match &amp;match, size_t pos, int level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal matching routine. <a href="#acb10ddb380fa79ce0a346360feffce11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d43ef3d3304bc786d75340eac860780">error</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating the expression was successfully compiled. <a href="#a3d43ef3d3304bc786d75340eac860780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd98016e2bda56b81308bdc907569ead">data</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The token stream representing the compiled regular expression. <a href="#afd98016e2bda56b81308bdc907569ead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pattern string as passed by the user. <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-doxygen/docs/api/classes/reg/ex/private">Private</a> members of a regular expression.</p>

<p>Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### Private() {#aa3f746ba480aec926ff3b83fdebb197a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Ex::Private::Private (std::string_view pat)</td>
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
<p>Creates the private part.</p>

<p>Definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3f746ba480aec926ff3b83fdebb197a">173</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa3f746ba480aec926ff3b83fdebb197a">Private</a>(std::string_view pat) : <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>(pat)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afd98016e2bda56b81308bdc907569ead">data</a>.reserve(100);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#afd98016e2bda56b81308bdc907569ead">data</a> and <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compile() {#a5ae763e5ab5231eae1133e68093c49be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Ex::Private::compile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Compiles a regular expression passed as a string into a stream of tokens that can be used for efficient searching.</p>

<p>Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ae763e5ab5231eae1133e68093c49be">197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5ae763e5ab5231eae1133e68093c49be">Ex::Private::compile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3d43ef3d3304bc786d75340eac860780">error</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afd98016e2bda56b81308bdc907569ead">data</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *start = <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *ps = start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevTokenPos=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tokenPos=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> addToken = [&amp;](<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afd98016e2bda56b81308bdc907569ead">data</a>.emplace_back(tok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getNextCharacter = [&amp;]() -&gt; <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs=*ps;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      cs=*ps;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'n'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);                      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'r'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(</span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">);                      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'t'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">);                      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'s'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">PToken::Kind::WhiteSpace</a>);  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">PToken::Kind::Alpha</a>);       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'w'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">PToken::Kind::AlphaNum</a>);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'d'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">PToken::Kind::Digit</a>);       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">PToken::Kind::BeginOfWord</a>); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">: result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">PToken::Kind::EndOfWord</a>);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'x'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'X'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">            uint16_t v=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;2 &amp;&amp; (cs=(*(ps+1)));i++) </span><span class="doxyHighlightComment">// 2 hex digits</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> d = (cs&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; cs&lt;=</span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight">) ? cs-</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">10 :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">                      (cs&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; cs&lt;=</span><span class="doxyHighlightCharLiteral">'F'</span><span class="doxyHighlight">) ? cs-</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">10 :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">                      (cs&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; cs&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">) ? cs-</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">    :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">                      -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d&gt;=0) { v&lt;&lt;=4; v|=d; ps++; } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">            result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(v);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">: ps--; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// backslash at the end of the pattern</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">          result = <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*ps))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// beginning of line (if first character of the pattern)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(ps==start ? <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">PToken::Kind::BeginOfLine</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(c));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// end of the line (if last character of the pattern)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(*(ps+1)==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight"> ? <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">PToken::Kind::EndOfLine</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(c));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// any character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">PToken::Kind::Any</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// begin of capture group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">PToken::Kind::BeginCapture</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// end of capture group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">PToken::Kind::EndCapture</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// character class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">          prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">          ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*ps==0) { <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> esc = *ps==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok = getNextCharacter();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">          ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!esc &amp;&amp; tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">                      tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>()==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// negated character class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">            addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">PToken::Kind::NegCharClass</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*ps==0) { <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = getNextCharacter();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">            ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">            addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">PToken::Kind::CharClass</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">          uint16_t numTokens=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*ps))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; *(ps+1)!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> &amp;&amp; *(ps+1)!=0) </span><span class="doxyHighlightComment">// range</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">              getNextCharacter();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">              ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> endTok = getNextCharacter();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">              ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()&gt;endTok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">                addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(endTok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>(),tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>())); </span><span class="doxyHighlightComment">// swap start and end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">                addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>(),endTok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">              numTokens++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// single char, from==to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>(),tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// special token, add as-is since from&gt;to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">                addToken(tok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">              numTokens++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*ps==0) { <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; } </span><span class="doxyHighlightComment">// expected at least a ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">            esc = *ps==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = getNextCharacter();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!esc &amp;&amp; tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                        tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()==</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint16_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end of character class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*ps==0) { <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; } </span><span class="doxyHighlightComment">// no ] found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">            ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// set the value of either NegCharClass or CharClass</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[prevTokenPos].setValue(numTokens);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// 0 or more</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// 1 or more</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// optional: 0 or 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prevTokenPos==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#afd98016e2bda56b81308bdc907569ead">data</a>[prevTokenPos].kind())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">PToken::Kind::BeginOfLine</a>:  </span><span class="doxyHighlightComment">// $*  or  $+ or  $?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">PToken::Kind::BeginOfWord</a>:  </span><span class="doxyHighlightComment">// \&lt;* or \&lt;+ or \&lt;?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">PToken::Kind::EndOfWord</a>:    </span><span class="doxyHighlightComment">// \&gt;* or \&gt;+ or \&gt;?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">PToken::Kind::Star</a>:         </span><span class="doxyHighlightComment">// **  or  *+ or  *?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">PToken::Kind::Optional</a>:     </span><span class="doxyHighlightComment">// ?*  or  ?+ or  ??</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// ok</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ddiff = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(tokenPos-prevTokenPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*ps==</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// convert &lt;pat&gt;+ -&gt; &lt;pat&gt;&lt;pat&gt;*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// turn a sequence of token [T1...Tn] followed by '+' into [T1..Tn T1..Tn T*]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//                          ddiff=n                                ^prevTokenPos</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#afd98016e2bda56b81308bdc907569ead">data</a>.resize(<a href="#afd98016e2bda56b81308bdc907569ead">data</a>.size()+ddiff);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">            std::copy_n(<a href="#afd98016e2bda56b81308bdc907569ead">data</a>.begin()+prevTokenPos,ddiff,<a href="#afd98016e2bda56b81308bdc907569ead">data</a>.begin()+tokenPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">            prevTokenPos+=ddiff;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">            tokenPos+=ddiff;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afd98016e2bda56b81308bdc907569ead">data</a>[prevTokenPos].kind()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">PToken::Kind::EndCapture</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// find the beginning of the capture range</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (prevTokenPos&gt;0 &amp;&amp; <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[prevTokenPos].kind()!=<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">PToken::Kind::BeginCapture</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">              prevTokenPos--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afd98016e2bda56b81308bdc907569ead">data</a>.insert(<a href="#afd98016e2bda56b81308bdc907569ead">data</a>.begin()+prevTokenPos,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">                      c==</span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight"> ? <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">PToken::Kind::Optional</a>) : <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">PToken::Kind::Star</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">          tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">          addToken(<a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a>(<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">PToken::Kind::End</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// turn a sequence of tokens [T1 T2 T3] followed by 'T*' or into [T* T1 T2 T3 TEND]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//                            ^prevTokenPos</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// same for 'T?'.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">        prevTokenPos = tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        addToken(getNextCharacter());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    ps++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//addToken(PToken(PToken::Kind::End));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">reg::PToken::Alpha</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">reg::PToken::AlphaNum</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">reg::PToken::Any</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">reg::PToken::asciiValue</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">reg::PToken::BeginCapture</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">reg::PToken::BeginOfLine</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">reg::PToken::BeginOfWord</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">reg::PToken::Character</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">reg::PToken::CharClass</a>, <a href="#afd98016e2bda56b81308bdc907569ead">data</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">reg::PToken::Digit</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">reg::PToken::End</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">reg::PToken::EndCapture</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">reg::PToken::EndOfLine</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">reg::PToken::EndOfWord</a>, <a href="#a3d43ef3d3304bc786d75340eac860780">error</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">reg::PToken::kind</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">reg::PToken::NegCharClass</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">reg::PToken::Optional</a>, <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">reg::PToken::Star</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">reg::PToken::value</a> and <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">reg::PToken::WhiteSpace</a>.
</div>
</div>

### matchAt() {#acb10ddb380fa79ce0a346360feffce11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Ex::Private::matchAt (size_t tokenPos, size_t tokenLen, std::string_view str, <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp; match, size_t pos, int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Internal matching routine.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">tokenPos</td>
<td class="doxyParamItemDescription"><p>Offset into the token stream.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">tokenLen</td>
<td class="doxyParamItemDescription"><p>The length of the token stream.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">str</td>
<td class="doxyParamItemDescription"><p>The input string to match against.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">match</td>
<td class="doxyParamItemDescription"><p>The object used to store the matching results.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">pos</td>
<td class="doxyParamItemDescription"><p>The position in the input string to start with matching</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">level</td>
<td class="doxyParamItemDescription"><p>Recursion level (used for debugging)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 181 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb10ddb380fa79ce0a346360feffce11">448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acb10ddb380fa79ce0a346360feffce11">Ex::Private::matchAt</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tokenPos,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tokenLen,std::string_view str,<a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp;<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"%d:matchAt(tokenPos=%zu, str='%s', pos=%zu)\n"</span><span class="doxyHighlight">,level,tokenPos,pos&lt;str.length() ? str.substr(pos).c_str() : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> isStartIdChar = [](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/reg/#a10c804e03b6d547a3748c3042fd5120b">isalpha</a>(c) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>      = [](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/reg/#ae874a7238f39cd3a0510485027015ef5">isalnum</a>(c) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> matchCharClass = [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,isStartIdChar,<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>](</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tp,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) -&gt; </span><span class="doxyHighlightKeywordType">bool</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok = <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[tp];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> negate = tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">PToken::Kind::NegCharClass</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">    uint16_t numFields = tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint16_t i=0;i&lt;numFields;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      tok = <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[++tp];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// first check for built-in ranges</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">PToken::Kind::Alpha</a>      &amp;&amp; isStartIdChar(c)) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">          (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">PToken::Kind::AlphaNum</a>   &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(c))      ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">          (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">PToken::Kind::WhiteSpace</a> &amp;&amp; <a href="/web-doxygen/docs/api/namespaces/reg/#ad6d291c9b035591b3bc2373dfbb14315">isspace</a>(c))  ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">          (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">PToken::Kind::Digit</a>      &amp;&amp; <a href="/web-doxygen/docs/api/namespaces/reg/#af7ff1342d768df1b4b668b072a33863f">isdigit</a>(c))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">        found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// user specified range</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">        uint16_t v = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint16_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a93203bf3f74828336b477ea31fde1a1c">from</a>()&lt;=v &amp;&amp; v&lt;=tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a2def1e14eeb96c08b25e4c906af071b6">to</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">          found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"matchCharClass(tp=%zu,c=%c (x%02x))=%d\n"</span><span class="doxyHighlight">,tp,c,c,negate?!found:found);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> negate ? !found : found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index = pos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> SequenceType { Star, Optional, OptionalRange };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> processSequence = [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,&amp;tokenPos,&amp;tokenLen,&amp;index,&amp;str,&amp;matchCharClass,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">                          &amp;isStartIdChar,&amp;<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>,&amp;<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,&amp;level,&amp;pos](SequenceType type) -&gt; </span><span class="doxyHighlightKeywordType">bool</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startIndex = index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = str.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok = <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[++tokenPos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a>) </span><span class="doxyHighlightComment">// 'x*' -&gt; eat x's</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c_tok = tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; str[index]==c_tok) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#aef9ece1aec9504adcf4deb03d803c378">isCharClass</a>()) </span><span class="doxyHighlightComment">// '[a-f0-4]* -&gt; eat matching characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; matchCharClass(tokenPos,str[index])) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos+=tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()+1; </span><span class="doxyHighlightComment">// skip over character ranges + end token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">PToken::Kind::Alpha</a>) </span><span class="doxyHighlightComment">// '\a*' -&gt; eat start id characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; isStartIdChar(str[index])) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">PToken::Kind::AlphaNum</a>) </span><span class="doxyHighlightComment">// '\w*' -&gt; eat id characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index])) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">PToken::Kind::WhiteSpace</a>) </span><span class="doxyHighlightComment">// '\s*' -&gt; eat spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; <a href="/web-doxygen/docs/api/namespaces/reg/#ad6d291c9b035591b3bc2373dfbb14315">isspace</a>(str[index])) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">PToken::Kind::Digit</a>) </span><span class="doxyHighlightComment">// '\d*' -&gt; eat digits</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;len &amp;&amp; <a href="/web-doxygen/docs/api/namespaces/reg/#af7ff1342d768df1b4b668b072a33863f">isdigit</a>(str[index])) { index++; </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">PToken::Kind::Any</a>) </span><span class="doxyHighlightComment">// '.*' -&gt; eat all</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==Optional) index++; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> index = str.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==OptionalRange &amp;&amp; tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">PToken::Kind::BeginCapture</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tokenStart = ++tokenPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tokenPos&lt;tokenLen &amp;&amp; <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[tokenPos].kind()!=<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">PToken::Kind::EndCapture</a>) { tokenPos++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> rangeMatch;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">      rangeMatch.<a href="/web-doxygen/docs/api/classes/reg/match/#a9c65c2d340c94527959a847251d67d1e">init</a>(str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = <a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a>(tokenStart,tokenPos,str,rangeMatch,index,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">        index+=rangeMatch.<a href="/web-doxygen/docs/api/classes/reg/match/#ad3ac6e9dcc408056ba2e32861da9294e">length</a>(); </span><span class="doxyHighlightComment">// (abc)? matches -&gt; eat all</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++; </span><span class="doxyHighlightComment">// skip over EndCapture</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    tokenPos++; </span><span class="doxyHighlightComment">// skip over end marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&gt;=startIndex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// pattern 'x*xy' should match 'xy' and 'xxxxy'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = <a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a>(tokenPos,tokenLen,str,<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,index,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.setMatch(pos,index-pos+<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">      index--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tokenPos&lt;tokenLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok = <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[tokenPos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"loop tokenPos=%zu token=%s\n"</span><span class="doxyHighlight">,tokenPos,tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9648ec9cffa7fc0d1ef165fc5882a552">kindStr</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a>) </span><span class="doxyHighlightComment">// match literal character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c_tok = tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || str[index]!=c_tok) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end of string, or non matching char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      index++,tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#aef9ece1aec9504adcf4deb03d803c378">isCharClass</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || !matchCharClass(tokenPos,str[index])) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">      index++,tokenPos+=tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">value</a>()+1; </span><span class="doxyHighlightComment">// skip over character ranges + end token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">PToken::Kind::Alpha</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || !isStartIdChar(str[index])) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">          index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">PToken::Kind::AlphaNum</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index])) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">          index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">PToken::Kind::WhiteSpace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || !<a href="/web-doxygen/docs/api/namespaces/reg/#ad6d291c9b035591b3bc2373dfbb14315">isspace</a>(str[index])) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">          index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">PToken::Kind::Digit</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() || !<a href="/web-doxygen/docs/api/namespaces/reg/#af7ff1342d768df1b4b668b072a33863f">isdigit</a>(str[index])) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">          index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">PToken::Kind::BeginOfLine</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index!=pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">PToken::Kind::EndOfLine</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;str.length()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">PToken::Kind::BeginOfWord</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"BeginOfWord: index=%zu isIdChar(%c)=%d prev.isIdChar(%c)=%d\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">              index,str[index],<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index]),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">              index&gt;0?str[index]-1:0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">              index&gt;0?<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index-1]):-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">              !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index]) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">              (index&gt;0 &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index-1]))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">PToken::Kind::EndOfWord</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"EndOfWord: index=%zu pos=%zu idIdChar(%c)=%d  prev.isIsChar(%c)=%d\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">              index,pos,str[index],<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index]),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">              index==0 ? 0 : str[index-1],</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">              index==0 ? -1 : <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index-1]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;str.length() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">              (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index]) || index==0 || !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(str[index-1]))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">PToken::Kind::BeginCapture</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"BeginCapture(%zu)\n"</span><span class="doxyHighlight">,index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.startCapture(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">PToken::Kind::EndCapture</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"EndCapture(%zu)\n"</span><span class="doxyHighlight">,index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.endCapture(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">PToken::Kind::Any</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;=str.length()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">          index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">PToken::Kind::Star</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> processSequence(Star);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">PToken::Kind::Optional</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tokenPos&lt;tokenLen-1 &amp;&amp; <a href="#afd98016e2bda56b81308bdc907569ead">data</a>[tokenPos+1].kind()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">PToken::Kind::BeginCapture</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> processSequence(OptionalRange); </span><span class="doxyHighlightComment">// (...)?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> processSequence(Optional); </span><span class="doxyHighlightComment">// x?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">      tokenPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.setMatch(pos,index-pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">reg::PToken::Alpha</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">reg::PToken::AlphaNum</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">reg::PToken::Any</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">reg::PToken::asciiValue</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">reg::PToken::BeginCapture</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">reg::PToken::BeginOfLine</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">reg::PToken::BeginOfWord</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">reg::PToken::Character</a>, <a href="#afd98016e2bda56b81308bdc907569ead">data</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">reg::PToken::Digit</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">reg::PToken::EndCapture</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">reg::PToken::EndOfLine</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">reg::PToken::EndOfWord</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a93203bf3f74828336b477ea31fde1a1c">reg::PToken::from</a>, <a href="/web-doxygen/docs/api/classes/reg/match/#a9c65c2d340c94527959a847251d67d1e">reg::Match::init</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#ae874a7238f39cd3a0510485027015ef5">reg::isalnum</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a10c804e03b6d547a3748c3042fd5120b">reg::isalpha</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#aef9ece1aec9504adcf4deb03d803c378">reg::PToken::isCharClass</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#af7ff1342d768df1b4b668b072a33863f">reg::isdigit</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#ad6d291c9b035591b3bc2373dfbb14315">reg::isspace</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">reg::PToken::kind</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9648ec9cffa7fc0d1ef165fc5882a552">reg::PToken::kindStr</a>, <a href="/web-doxygen/docs/api/classes/reg/match/#ad3ac6e9dcc408056ba2e32861da9294e">reg::Match::length</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a>, <a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">reg::PToken::NegCharClass</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">reg::PToken::Optional</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">reg::PToken::Star</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a2def1e14eeb96c08b25e4c906af071b6">reg::PToken::to</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#ac897faa4d75c143ca24924a5754aa369">reg::PToken::value</a> and <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">reg::PToken::WhiteSpace</a>.

Referenced by <a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### data {#afd98016e2bda56b81308bdc907569ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PToken&gt; reg::Ex::Private::data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>The token stream representing the compiled regular expression.</p>

<p>Definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd98016e2bda56b81308bdc907569ead">188</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;PToken&gt; <a href="#afd98016e2bda56b81308bdc907569ead">data</a>; </span><span class="doxyHighlightComment">// compiled pattern</span></span></div>

</div>


Referenced by <a href="#a5ae763e5ab5231eae1133e68093c49be">compile</a>, <a href="#acb10ddb380fa79ce0a346360feffce11">matchAt</a> and <a href="#aa3f746ba480aec926ff3b83fdebb197a">Private</a>.
</div>
</div>

### error {#a3d43ef3d3304bc786d75340eac860780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Ex::Private::error = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Flag indicating the expression was successfully compiled.</p>

<p>Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d43ef3d3304bc786d75340eac860780">185</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3d43ef3d3304bc786d75340eac860780">error</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a5ae763e5ab5231eae1133e68093c49be">compile</a>.
</div>
</div>

### pattern {#a68af93bd4fbea3f82ee8e36af3a6e68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string reg::Ex::Private::pattern</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>The pattern string as passed by the user.</p>

<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a68af93bd4fbea3f82ee8e36af3a6e68b">pattern</a>;</span></span></div>

</div>


Referenced by <a href="#a5ae763e5ab5231eae1133e68093c49be">compile</a> and <a href="#aa3f746ba480aec926ff3b83fdebb197a">Private</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
