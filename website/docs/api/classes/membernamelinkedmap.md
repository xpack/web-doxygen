---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/membernamelinkedmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemberNameLinkedMap` Class Reference

<p>Ordered dictionary of <a href="/web-doxygen/docs/api/classes/membername">MemberName</a> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class MemberNameLinkedMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/membername-h">src/membername.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap&lt;T, Hash, KeyEqual, Map&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Container class representing a vector of objects with keys. <a href="/web-doxygen/docs/api/classes/linkedmap/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membername/#ad29b8b25d2a76b5bcab3ebd6a6653de0">MemberName::Ptr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6004257529aa381892db1f8ae282ee29">take</a> (const QCString &amp;key, const MemberDef *value)</td>
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

<p>Ordered dictionary of <a href="/web-doxygen/docs/api/classes/membername">MemberName</a> objects.</p>

<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### take() {#a6004257529aa381892db1f8ae282ee29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberName::Ptr MemberNameLinkedMap::take (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * value)</td>
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



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6004257529aa381892db1f8ae282ee29">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/membername/#ad29b8b25d2a76b5bcab3ebd6a6653de0">MemberName::Ptr</a> <a href="#a6004257529aa381892db1f8ae282ee29">take</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/membername/#ad29b8b25d2a76b5bcab3ebd6a6653de0">MemberName::Ptr</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/membername">MemberName</a> *mn = <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">find</a>(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if(mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#ada97200941011de3b6714f39df5fc29c">begin</a>(),mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#ae3020460ff555c0e59434bfe512f8fbd">end</a>(),[&amp;value](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;el) { return el.get()==value; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#ae3020460ff555c0e59434bfe512f8fbd">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">          it-&gt;swap(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">          mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#a78d241ba177183be74c63376c382a5fc">erase</a>(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mn-&gt;<a href="/web-doxygen/docs/api/classes/membername/#ad47e17450a0c958521210bfcf27e05d2">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/linkedmap/#a6150feb21a667df3826df38c1a0878fa">del</a>(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/membername/#ada97200941011de3b6714f39df5fc29c">MemberName::begin</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#a6150feb21a667df3826df38c1a0878fa">LinkedMap&lt; MemberName &gt;::del</a>, <a href="/web-doxygen/docs/api/classes/membername/#ad47e17450a0c958521210bfcf27e05d2">MemberName::empty</a>, <a href="/web-doxygen/docs/api/classes/membername/#ae3020460ff555c0e59434bfe512f8fbd">MemberName::end</a>, <a href="/web-doxygen/docs/api/classes/membername/#a78d241ba177183be74c63376c382a5fc">MemberName::erase</a> and <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; MemberName &gt;::find</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
