---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/symbolmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolMap` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class T&gt;
class SymbolMap&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/symbolmap-h">src/symbolmap.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> = T *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> = std::vector&lt; <a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad455155d32de992ca2ef948290d2797d">Map</a> = std::unordered_map&lt; std::string, <a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a908627b07109135e822be81c8cd570e9">iterator</a> = typename Map::iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a> = typename Map::const_iterator</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ee5036f5adbd147a02e4aa476fc8b72">add</a> (const QCString &amp;name, Ptr def)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a symbol <em>def</em> into the map under key <em>name</em>. <a href="#a5ee5036f5adbd147a02e4aa476fc8b72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36b000d1d74ec4820b0d1c3a57dd645c">remove</a> (const QCString &amp;name, Ptr def)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a symbol <em>def</em> from the map that was stored under key <em>name</em>. <a href="#a36b000d1d74ec4820b0d1c3a57dd645c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a84904cdc40a6daca784500b454fbc813">find</a> (const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a908627b07109135e822be81c8cd570e9">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9cd4fa2b43e0199d4cef45ff3cbb37e">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a908627b07109135e822be81c8cd570e9">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6069b0857a4c760cefa51b569820156c">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a740d72033e533f71065ea8cf3b3f3d2a">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5f1eb80c8797531fa0421d9bf68e8dd">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeed554c8b958d2b8c6dcba5611d2b8cf">empty</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad455155d32de992ca2ef948290d2797d">Map</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44148f88041734dd12f69521dc25e174">m_noMatch</a></td>
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



<p>Class implementing a symbol map that maps symbol names to objects. Symbol names do not have to be unique. Supports adding symbols with <a href="#a5ee5036f5adbd147a02e4aa476fc8b72">add()</a>, removing symbols with <a href="#a36b000d1d74ec4820b0d1c3a57dd645c">remove()</a>, and finding symbols with <a href="#a84904cdc40a6daca784500b454fbc813">find()</a>.</p>


<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a53fbe4b99c651adaaf27f506450a9a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SymbolMap&lt; T &gt;::const_iterator =  typename Map::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53fbe4b99c651adaaf27f506450a9a1d">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Map::const_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#a908627b07109135e822be81c8cd570e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SymbolMap&lt; T &gt;::iterator =  typename Map::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a908627b07109135e822be81c8cd570e9">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a908627b07109135e822be81c8cd570e9">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Map::iterator;</span></span></div>

</div>

</div>
</div>

### Map {#ad455155d32de992ca2ef948290d2797d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SymbolMap&lt; T &gt;::Map =  std::unordered_map&lt;std::string,VectorPtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad455155d32de992ca2ef948290d2797d">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad455155d32de992ca2ef948290d2797d">Map</a> = std::unordered_map&lt;std::string,VectorPtr&gt;;</span></span></div>

</div>

</div>
</div>

### Ptr {#af163fde1625af00fe48af2a874b29204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SymbolMap&lt; T &gt;::Ptr =  T *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af163fde1625af00fe48af2a874b29204">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> = T *;</span></span></div>

</div>

</div>
</div>

### VectorPtr {#a9051b6931ae769df892b5755f5c0a0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SymbolMap&lt; T &gt;::VectorPtr =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9051b6931ae769df892b5755f5c0a0e7">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a5ee5036f5adbd147a02e4aa476fc8b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolMap&lt; T &gt;::add (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> def)</td>
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

<p>Add a symbol <em>def</em> into the map under key <em>name</em>.</p>

<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ee5036f5adbd147a02e4aa476fc8b72">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5ee5036f5adbd147a02e4aa476fc8b72">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,<a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;second.push_back(def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.emplace(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a>({def}));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### begin() {#ab9cd4fa2b43e0199d4cef45ff3cbb37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator SymbolMap&lt; T &gt;::begin ()</td>
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



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9cd4fa2b43e0199d4cef45ff3cbb37e">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a908627b07109135e822be81c8cd570e9">iterator</a> <a href="#ab9cd4fa2b43e0199d4cef45ff3cbb37e">begin</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.begin();  }</span></span></div>

</div>


<p>Reference <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>.</p>

</div>
</div>

### begin() {#a740d72033e533f71065ea8cf3b3f3d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator SymbolMap&lt; T &gt;::begin ()</td>
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



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a740d72033e533f71065ea8cf3b3f3d2a">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a> <a href="#a740d72033e533f71065ea8cf3b3f3d2a">begin</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.cbegin(); }</span></span></div>

</div>


<p>Reference <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>.</p>

</div>
</div>

### empty() {#aeed554c8b958d2b8c6dcba5611d2b8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolMap&lt; T &gt;::empty ()</td>
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



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeed554c8b958d2b8c6dcba5611d2b8cf">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aeed554c8b958d2b8c6dcba5611d2b8cf">empty</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.empty();  }</span></span></div>

</div>


<p>Reference <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>.</p>

</div>
</div>

### end() {#a6069b0857a4c760cefa51b569820156c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator SymbolMap&lt; T &gt;::end ()</td>
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



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6069b0857a4c760cefa51b569820156c">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a908627b07109135e822be81c8cd570e9">iterator</a> <a href="#a6069b0857a4c760cefa51b569820156c">end</a>()               { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.end();    }</span></span></div>

</div>


<p>Reference <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>.</p>

</div>
</div>

### end() {#ad5f1eb80c8797531fa0421d9bf68e8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator SymbolMap&lt; T &gt;::end ()</td>
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



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5f1eb80c8797531fa0421d9bf68e8dd">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a53fbe4b99c651adaaf27f506450a9a1d">const_iterator</a> <a href="#ad5f1eb80c8797531fa0421d9bf68e8dd">end</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.cend();   }</span></span></div>

</div>


<p>Reference <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>.</p>

</div>
</div>

### find() {#a84904cdc40a6daca784500b454fbc813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorPtr &amp; SymbolMap&lt; T &gt;::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>Find the list of symbols stored under key <em>name</em> Returns a pair of iterators pointing to the start and end of the range of matching symbols</p>


<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84904cdc40a6daca784500b454fbc813">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> &amp;<a href="#a84904cdc40a6daca784500b454fbc813">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(<a href="#a44148f88041734dd12f69521dc25e174">m_noMatch</a>.empty());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it==<a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.end() ? <a href="#a44148f88041734dd12f69521dc25e174">m_noMatch</a> : it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a>, <a href="#a44148f88041734dd12f69521dc25e174">SymbolMap&lt; T &gt;::m_noMatch</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### remove() {#a36b000d1d74ec4820b0d1c3a57dd645c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolMap&lt; T &gt;::remove (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> def)</td>
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

<p>Remove a symbol <em>def</em> from the map that was stored under key <em>name</em>.</p>

<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36b000d1d74ec4820b0d1c3a57dd645c">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a36b000d1d74ec4820b0d1c3a57dd645c">remove</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,<a href="#af163fde1625af00fe48af2a874b29204">Ptr</a> def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it1 = <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it1!=<a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> &amp;v = it1-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it2 = std::find(v.begin(),v.end(),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it2!=v.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">          v.erase(it2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>.erase(it1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">SymbolMap&lt; T &gt;::m_map</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_map {#adb4e4e42ab3d988f61ab9e6a3f057bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Map SymbolMap&lt; T &gt;::m_map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad455155d32de992ca2ef948290d2797d">Map</a> <a href="#adb4e4e42ab3d988f61ab9e6a3f057bcf">m_map</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5ee5036f5adbd147a02e4aa476fc8b72">SymbolMap&lt; T &gt;::add</a>, <a href="#ab9cd4fa2b43e0199d4cef45ff3cbb37e">SymbolMap&lt; T &gt;::begin</a>, <a href="#a740d72033e533f71065ea8cf3b3f3d2a">SymbolMap&lt; T &gt;::begin</a>, <a href="#aeed554c8b958d2b8c6dcba5611d2b8cf">SymbolMap&lt; T &gt;::empty</a>, <a href="#a6069b0857a4c760cefa51b569820156c">SymbolMap&lt; T &gt;::end</a>, <a href="#ad5f1eb80c8797531fa0421d9bf68e8dd">SymbolMap&lt; T &gt;::end</a>, <a href="#a84904cdc40a6daca784500b454fbc813">SymbolMap&lt; T &gt;::find</a> and <a href="#a36b000d1d74ec4820b0d1c3a57dd645c">SymbolMap&lt; T &gt;::remove</a>.</p>

</div>
</div>

### m\_noMatch {#a44148f88041734dd12f69521dc25e174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorPtr SymbolMap&lt; T &gt;::m_noMatch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44148f88041734dd12f69521dc25e174">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9051b6931ae769df892b5755f5c0a0e7">VectorPtr</a> <a href="#a44148f88041734dd12f69521dc25e174">m_noMatch</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a84904cdc40a6daca784500b454fbc813">SymbolMap&lt; T &gt;::find</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/symbolmap-h">symbolmap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
