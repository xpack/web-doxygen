---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmt/formatter-a295d5763d866422fbb9f0f73b5aeb1a
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `formatter` Struct Template Reference

adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a> <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct fmt::formatter&lt;MemberType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/message-h">src/message.h</a>&gt;
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;T&gt;</a></td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2f84f849eb72e0cf0976a1482a130d">format</a> (MemberType mtype, format_context &amp;ctx) const</td>
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

## Description {#details}

adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a>

Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### format() {#a0c2f84f849eb72e0cf0976a1482a130d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto fmt::formatter&lt; MemberType &gt;::format (<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a> mtype, format_context &amp; ctx)</td>
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



Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c2f84f849eb72e0cf0976a1482a130d">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a0c2f84f849eb72e0cf0976a1482a130d">format</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a> mtype, format_context&amp; ctx)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string result=</span><span class="doxyHighlightStringLiteral">"Unknown"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (mtype)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a>:      result=</span><span class="doxyHighlightStringLiteral">"Define"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">MemberType::Function</a>:    result=</span><span class="doxyHighlightStringLiteral">"Function"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>:    result=</span><span class="doxyHighlightStringLiteral">"Variable"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">MemberType::Typedef</a>:     result=</span><span class="doxyHighlightStringLiteral">"Typedef"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>: result=</span><span class="doxyHighlightStringLiteral">"Enumeration"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>:   result=</span><span class="doxyHighlightStringLiteral">"EnumValue"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">MemberType::Signal</a>:      result=</span><span class="doxyHighlightStringLiteral">"Signal"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">MemberType::Slot</a>:        result=</span><span class="doxyHighlightStringLiteral">"Slot"</span><span class="doxyHighlight">;        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">MemberType::Friend</a>:      result=</span><span class="doxyHighlightStringLiteral">"Friend"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">MemberType::DCOP</a>:        result=</span><span class="doxyHighlightStringLiteral">"DCOP"</span><span class="doxyHighlight">;        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">MemberType::Property</a>:    result=</span><span class="doxyHighlightStringLiteral">"Property"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">MemberType::Event</a>:       result=</span><span class="doxyHighlightStringLiteral">"Event"</span><span class="doxyHighlight">;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">MemberType::Interface</a>:   result=</span><span class="doxyHighlightStringLiteral">"Interface"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">MemberType::Service</a>:     result=</span><span class="doxyHighlightStringLiteral">"Service"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">MemberType::Sequence</a>:    result=</span><span class="doxyHighlightStringLiteral">"Sequence"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">MemberType::Dictionary</a>:  result=</span><span class="doxyHighlightStringLiteral">"Dictionary"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;std::string&gt;::format</a>(result, ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">DCOP</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">Define</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">Dictionary</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">Enumeration</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">Event</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">Friend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">Function</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">Interface</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">Property</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">Sequence</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">Service</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">Signal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">Slot</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/message-h">message.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
