---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlattriblist
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `HtmlAttribList` Class Reference

Class representing a list of HTML attributes. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class HtmlAttribList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htmlattrib-h">src/htmlattrib.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; HtmlAttrib &gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c837fb5c6a666618137b335fe89760">mergeAttribute</a> (const QCString &amp;optName, const QCString &amp;optValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1a465884de9fb878a7d738ef578aca">toString</a> (QCString *pAltValue=nullptr) const</td>
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

Class representing a list of HTML attributes.

Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### mergeAttribute() {#ac7c837fb5c6a666618137b335fe89760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlAttribList::mergeAttribute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; optName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; optValue)</td>
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



Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7c837fb5c6a666618137b335fe89760">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac7c837fb5c6a666618137b335fe89760">mergeAttribute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;optName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;optValue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ab6c94b68ae7d5509e621425954c7fc50">begin</a>(),<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">                           [&amp;optName](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> opt.name==optName; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>()) </span><span class="doxyHighlightComment">// attribute name already in the list: append values</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;value += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + optValue;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// attribute name not yet in the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">        emplace_back(optName,optValue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ab6c94b68ae7d5509e621425954c7fc50">begin</a> and <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>.
</div>
</div>

### toString() {#a4c1a465884de9fb878a7d738ef578aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlAttribList::toString (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pAltValue=nullptr)</td>
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



Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c1a465884de9fb878a7d738ef578aca">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4c1a465884de9fb878a7d738ef578aca">toString</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pAltValue = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;att : *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!att.value.isEmpty())  </span><span class="doxyHighlightComment">// ignore attribute without values as they</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightComment">// are not XHTML compliant, with the exception</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightComment">// of the alt attribute with the img tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (att.name==</span><span class="doxyHighlightStringLiteral">"alt"</span><span class="doxyHighlight"> &amp;&amp; pAltValue) </span><span class="doxyHighlightComment">// optionally return the value of alt separately</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// need to convert &lt;img&gt; to &lt;object&gt; for SVG images,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// which do not support the alt attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">            *pAltValue = att.value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+att.name+</span><span class="doxyHighlightStringLiteral">"=\""</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(att.value)+</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (att.name==</span><span class="doxyHighlightStringLiteral">"open"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// The open attribute is a boolean attribute.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// Specifies that the details should be visible (open) to the user</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// As it is a boolean attribute the initialization value is of no interest</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+att.name+</span><span class="doxyHighlightStringLiteral">"=\"true\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (att.name==</span><span class="doxyHighlightStringLiteral">"nowrap"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// In XHTML, attribute minimization is forbidden, and the nowrap attribute must be defined as &lt;td nowrap="nowrap"&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+att.name+</span><span class="doxyHighlightStringLiteral">"=\"nowrap\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af2c6ce63224938d2b3956b3e068bfa8a">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ab06971ee32204757c136a8239efbe14c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a6185cb6e624208c3f4ffc97ac506b992">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ae8045f0e970c89316252774afa7ba6e7">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a3185ae1b9ec057a569c7fe2028bde639">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a57828df222d35104882456ca963de01b">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa58041765d9fdcee90946dacbeb78486">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a26419facc6206c5d26e4973ffe74e364">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aed1aaa1f3a2968aab022220e3472b438">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ad1853fe217d1db39ead0b09185688cca">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a4f71b7f0fd9236e38d92839fe07e9cb9">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a8b1f0d351532074efc4bc79b3da7b4c4">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa913c394c4823af2ed130551750922fe">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a7403c2c1184b33f47de3b9257b929e41">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#acc9d92c357105ee35917a0ef6a1a847d">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ace45195acd5464fbc29281fd8d44c66d">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aad17706c575aed161325cc59a01003f7">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a104c3ca52ddda7596a073155996e8214">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
