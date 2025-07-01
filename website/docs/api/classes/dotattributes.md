---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotattributes
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotAttributes` Class Reference

Class representing an attribute list of a dot graph object. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DotAttributes { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotattributes-h">src/dotattributes.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87143b014cd674f622db1f2c2e0b28a">DotAttributes</a> (const QCString &amp;input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Creates an instance of a DotAttribute list given its initial string representation. <a href="#aa87143b014cd674f622db1f2c2e0b28a">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee5c25bd25303a97739d3c43ee72449">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Return the string representation of the attribute list. <a href="#aaee5c25bd25303a97739d3c43ee72449">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379cba80b5c667d8d41d85426c4f5376">updateValue</a> (const QCString &amp;key, const QCString &amp;inpValue)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a></td>
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

Class representing an attribute list of a dot graph object.

Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DotAttributes() {#aa87143b014cd674f622db1f2c2e0b28a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotAttributes::DotAttributes (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input)</td>
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

Creates an instance of a DotAttribute list given its initial string representation.

Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa87143b014cd674f622db1f2c2e0b28a">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa87143b014cd674f622db1f2c2e0b28a">DotAttributes</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input) : <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>(input) {}</span></span></div>

</div>


Reference <a href="#aeb0354da75e7992d624891531ebef8e2">m\_input</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### str() {#aaee5c25bd25303a97739d3c43ee72449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotAttributes::str ()</td>
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

Return the string representation of the attribute list.

Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaee5c25bd25303a97739d3c43ee72449">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aaee5c25bd25303a97739d3c43ee72449">str</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>; }</span></span></div>

</div>


Reference <a href="#aeb0354da75e7992d624891531ebef8e2">m\_input</a>.

Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.
</div>
</div>

### updateValue() {#a379cba80b5c667d8d41d85426c4f5376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotAttributes::updateValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inpValue)</td>
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




update a given attribute with a new value. If the attribute is not found a new attribute will be appended.

Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a379cba80b5c667d8d41d85426c4f5376">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a379cba80b5c667d8d41d85426c4f5376">updateValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inpValue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// look for key\s*=</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string regStr = key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+R</span><span class="doxyHighlightStringLiteral">"(\s*=)";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re { regStr };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string s = <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,match,re)) </span><span class="doxyHighlightComment">// replace existing attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len      = s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startPos = match.position()+match.length(); </span><span class="doxyHighlightComment">// position after =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos      = startPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;len &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(s[pos])) pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;len &amp;&amp; s[pos]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// quoted value, search for end quote, ignoring escaped quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=s[pos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">          pos++; </span><span class="doxyHighlightComment">// skip over start quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;len &amp;&amp; (s[pos]!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> || (s[pos]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; pc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">))) pc=s[pos++];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;len) pos++; </span><span class="doxyHighlightComment">// skip over end quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// unquoted value, search for attribute separator (space,comma, or semicolon)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;len &amp;&amp; s[pos]!=</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> &amp;&amp; s[pos]!=</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight"> &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(s[pos])) pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inpValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">          value = <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>.mid(startPos,pos-startPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">          value = inpValue;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// pos is now the position after the value, so replace the part between [start..pos) with the new value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>=<a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>.left(startPos)+value.<a href="/web-doxygen/docs/api/classes/qcstring/#af428b9307683dc2c090f7d837138b438">quoted</a>()+<a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>.mid(pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// append new attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inpValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>.isEmpty()) <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>+=</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>+=key+</span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">+inpValue.<a href="/web-doxygen/docs/api/classes/qcstring/#af428b9307683dc2c090f7d837138b438">quoted</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aeb0354da75e7992d624891531ebef8e2">m\_input</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af428b9307683dc2c090f7d837138b438">QCString::quoted</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_input {#aeb0354da75e7992d624891531ebef8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotAttributes::m_input</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb0354da75e7992d624891531ebef8e2">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aeb0354da75e7992d624891531ebef8e2">m_input</a>;</span></span></div>

</div>


Referenced by <a href="#aa87143b014cd674f622db1f2c2e0b28a">DotAttributes</a>, <a href="#aaee5c25bd25303a97739d3c43ee72449">str</a> and <a href="#a379cba80b5c667d8d41d85426c4f5376">updateValue</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
