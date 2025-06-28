---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/definemanager/definesperfile
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DefinesPerFile` Class Reference

<p>Local class used to hold the defines for a single file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DefineManager::DefinesPerFile { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f786619e5a63c13d9f0d6233914675">DefinesPerFile</a> (DefineManager *parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an empty container for defines. <a href="#a28f786619e5a63c13d9f0d6233914675">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d40ea9678233df1c4deaa66e8e77ae">addInclude</a> (const std::string &amp;fileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf26b848a690b17547d913dbb49848e6">store</a> (const DefineMap &amp;fromMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0cd2f06be4aa715612884608c79c90f">retrieve</a> (DefineMap &amp;toMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a> (DefineMap &amp;toMap, StringUnorderedSet &amp;includeStack)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c56c7777eff7ce2d9329353e32296c">stored</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m_parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62829771df09db4d985c0938a2dd17c5">m_defines</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a7690feba1d8603e2689c032a263e7">m_includedFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3720c4590f5e5afbecb80c77c118bb35">m_stored</a> = false</td>
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

<p>Local class used to hold the defines for a single file.</p>

<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### DefinesPerFile() {#a28f786619e5a63c13d9f0d6233914675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefineManager::DefinesPerFile::DefinesPerFile (<a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a> * parent)</td>
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
<p>Creates an empty container for defines.</p>

<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28f786619e5a63c13d9f0d6233914675">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a28f786619e5a63c13d9f0d6233914675">DefinesPerFile</a>(<a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">          : <a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m_parent</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>

</div>


References <a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m&#95;parent</a> and <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>.

Referenced by <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInclude() {#a01d40ea9678233df1c4deaa66e8e77ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::DefinesPerFile::addInclude (const std::string &amp; fileName)</td>
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


<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01d40ea9678233df1c4deaa66e8e77ae">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a01d40ea9678233df1c4deaa66e8e77ae">addInclude</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ac3a7690feba1d8603e2689c032a263e7">m_includedFiles</a>.insert(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>

</div>


Reference <a href="#ac3a7690feba1d8603e2689c032a263e7">m&#95;includedFiles</a>.
</div>
</div>

### retrieve() {#ad0cd2f06be4aa715612884608c79c90f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::DefinesPerFile::retrieve (<a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp; toMap)</td>
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


<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0cd2f06be4aa715612884608c79c90f">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad0cd2f06be4aa715612884608c79c90f">retrieve</a>(<a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;toMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> includeStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>(toMap,includeStack);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>

</div>


Reference <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.
</div>
</div>

### retrieveRec() {#a6e51ee0c21e8152703c154432f78148a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::DefinesPerFile::retrieveRec (<a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp; toMap, <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> &amp; includeStack)</td>
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


<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e51ee0c21e8152703c154432f78148a">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>(<a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;toMap,<a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> &amp;includeStack)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("  retrieveRec #includedFiles=%zu\n",m_includedFiles.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> incFile : <a href="#ac3a7690feba1d8603e2689c032a263e7">m_includedFiles</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a28f786619e5a63c13d9f0d6233914675">DefinesPerFile</a> *dpf = <a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m_parent</a>-&gt;find(incFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dpf &amp;&amp; includeStack.find(incFile)==includeStack.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">              includeStack.insert(incFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">              dpf-&gt;<a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>(toMap,includeStack);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//printf("  retrieveRec: processing include %s: #toMap=%zu\n",qPrint(incFile),toMap.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,define] : <a href="#a62829771df09db4d985c0938a2dd17c5">m_defines</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">            toMap.emplace(name,define);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>

</div>


References <a href="#a28f786619e5a63c13d9f0d6233914675">DefinesPerFile</a>, <a href="#a62829771df09db4d985c0938a2dd17c5">m&#95;defines</a>, <a href="#ac3a7690feba1d8603e2689c032a263e7">m&#95;includedFiles</a>, <a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m&#95;parent</a> and <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.

Referenced by <a href="#ad0cd2f06be4aa715612884608c79c90f">retrieve</a> and <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.
</div>
</div>

### store() {#aaf26b848a690b17547d913dbb49848e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::DefinesPerFile::store (const <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp; fromMap)</td>
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


<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf26b848a690b17547d913dbb49848e6">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaf26b848a690b17547d913dbb49848e6">store</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;fromMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,define] : fromMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a62829771df09db4d985c0938a2dd17c5">m_defines</a>.emplace(name,define);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("  m_defines.size()=%zu\n",m_defines.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a3720c4590f5e5afbecb80c77c118bb35">m_stored</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>

</div>


References <a href="#a62829771df09db4d985c0938a2dd17c5">m&#95;defines</a> and <a href="#a3720c4590f5e5afbecb80c77c118bb35">m&#95;stored</a>.
</div>
</div>

### stored() {#a72c56c7777eff7ce2d9329353e32296c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefineManager::DefinesPerFile::stored ()</td>
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


<p>Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72c56c7777eff7ce2d9329353e32296c">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a72c56c7777eff7ce2d9329353e32296c">stored</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3720c4590f5e5afbecb80c77c118bb35">m_stored</a>; }</span></span></div>

</div>


Reference <a href="#a3720c4590f5e5afbecb80c77c118bb35">m&#95;stored</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;defines {#a62829771df09db4d985c0938a2dd17c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefineMap DefineManager::DefinesPerFile::m_defines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62829771df09db4d985c0938a2dd17c5">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> <a href="#a62829771df09db4d985c0938a2dd17c5">m_defines</a>;</span></span></div>

</div>


Referenced by <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a> and <a href="#aaf26b848a690b17547d913dbb49848e6">store</a>.
</div>
</div>

### m&#95;includedFiles {#ac3a7690feba1d8603e2689c032a263e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedSet DefineManager::DefinesPerFile::m_includedFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3a7690feba1d8603e2689c032a263e7">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> <a href="#ac3a7690feba1d8603e2689c032a263e7">m_includedFiles</a>;</span></span></div>

</div>


Referenced by <a href="#a01d40ea9678233df1c4deaa66e8e77ae">addInclude</a> and <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.
</div>
</div>

### m&#95;parent {#a3ce942a3afdfbec6ad3eea0096c2c012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefineManager* DefineManager::DefinesPerFile::m_parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ce942a3afdfbec6ad3eea0096c2c012">164</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a> *<a href="#a3ce942a3afdfbec6ad3eea0096c2c012">m_parent</a>;</span></span></div>

</div>


Referenced by <a href="#a28f786619e5a63c13d9f0d6233914675">DefinesPerFile</a> and <a href="#a6e51ee0c21e8152703c154432f78148a">retrieveRec</a>.
</div>
</div>

### m&#95;stored {#a3720c4590f5e5afbecb80c77c118bb35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefineManager::DefinesPerFile::m_stored = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3720c4590f5e5afbecb80c77c118bb35">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3720c4590f5e5afbecb80c77c118bb35">m_stored</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#aaf26b848a690b17547d913dbb49848e6">store</a> and <a href="#a72c56c7777eff7ce2d9329353e32296c">stored</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
