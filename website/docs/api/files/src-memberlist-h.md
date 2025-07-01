---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/memberlist-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `memberlist.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;algorithm&gt;
#include &lt;utility&gt;
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
A vector of <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> object. <a href="/web-doxygen/docs/api/classes/membervector/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
A list of <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> objects as shown in documentation sections. <a href="/web-doxygen/docs/api/classes/memberlist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlinkedrefmap">MemberLinkedRefMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlists">MemberLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a> (const MemberDef *c1, const MemberDef *c2)</td>
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

### genericCompareMembers() {#a167ee264b79050f2a7adc66a8c0e999d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int genericCompareMembers (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * c1, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * c2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>, definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/memberlist-cpp">memberlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">48</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *c1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *c2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sortConstructorsFirst = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SORT_MEMBERS_CTORS_1ST);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sortConstructorsFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ord1 = c1-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a196a099fba755a0586625635e40e9c58">isConstructor</a>() ? 2 : (c1-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0807e7d46f56761eb33db77778289c11">isDestructor</a>() ? 1 : 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ord2 = c2-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a196a099fba755a0586625635e40e9c58">isConstructor</a>() ? 2 : (c2-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0807e7d46f56761eb33db77778289c11">isDestructor</a>() ? 1 : 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ord1 &gt; ord2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ord2 &gt; ord1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// sort on name, first case in-sensitive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cmp = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(c1-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),c2-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then on qualified name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmp==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    cmp = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(c1-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),c2-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then on argument list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmp==0 &amp;&amp; !c1-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !c2-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    cmp = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(c1-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>(),c2-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then on file in which the item is defined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmp==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    cmp = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(c1-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),c2-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then on line number at which the member is defined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmp==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    cmp = c1-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()-c2-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cmp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a196a099fba755a0586625635e40e9c58">MemberDef::isConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0807e7d46f56761eb33db77778289c11">MemberDef::isDestructor</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a> and <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/membervector/#a55bc8544d134138efb4a3aaf8518c32f">MemberVector::lessThan</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
