---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/cache
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Cache` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename K, typename V&gt;
class Cache&lt;K, V&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/cache-h">src/cache.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a> = std::pair&lt; K, V &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79258c643559f458b14ecb02a0258d00">iterator</a> = typename std::list&lt; <a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a> &gt;::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a> = typename std::list&lt; <a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a> &gt;::const_iterator</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aaa77900cf0925ea6e46653361bc6be29">Cache</a> (size_t capacity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
creates a cache that can hold <em>capacity</em> elements <a href="#aaa77900cf0925ea6e46653361bc6be29">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">V *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1cf01dfdbe1b56e62c25112e771b23fa">insert</a> (const K &amp;key, V &amp;&amp;value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Inserts <em>value</em> under <em>key</em> in the cache. <a href="#a1cf01dfdbe1b56e62c25112e771b23fa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">V *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2346678720d2078c031e7ea436e402b6">insert</a> (const K &amp;key, const V &amp;value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Inserts <em>value</em> under <em>key</em> in the cache. <a href="#a2346678720d2078c031e7ea436e402b6">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3a7d2f92c1e3652b0279dcafe563f8e">remove</a> (const K &amp;key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">V *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find</a> (const K &amp;key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b8abd9f417e818217ba17f9756f41eb">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the number of values stored in the cache. <a href="#a8b8abd9f417e818217ba17f9756f41eb">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62ce1e1112e08368aff14b6627d2d039">capacity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the maximum number of values that can be stored in the cache. <a href="#a62ce1e1112e08368aff14b6627d2d039">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace97657a7c672dcc74d30e43c4006ea7">hits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns how many of the <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find()</a> calls did find a value in the cache. <a href="#ace97657a7c672dcc74d30e43c4006ea7">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">misses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns how many of the <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find()</a> calls did not found a value in the cache. <a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa0c3a5019640bfd305277ac83ff553f">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Clears all values in the cache. <a href="#aaa0c3a5019640bfd305277ac83ff553f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a79258c643559f458b14ecb02a0258d00">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a710ca4c838a720d74a5a9063df23a27e">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a79258c643559f458b14ecb02a0258d00">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3328cf128d88cc86cbf81ce38dc81f0f">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5212a44b518fd416891d0a0751c8ae78">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a980ba5495fea787d5e88a5f6a24a2f4b">end</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4da60b9993165ac0170ae98b91cd9299">resize</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a779e62967f4cc5217b0fdc4158ca4311">m_capacity</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::list&lt; <a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unordered_map&lt; K, <a href="#a79258c643559f458b14ecb02a0258d00">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a848baa79896ab6ebca4433c41b0098a0">m_hits</a> =0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K, typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">m_misses</a> =0</td>
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



Fixed size cache for value type V using keys of type K.

When the maximum capacity has reached, the least recently used value is removed from the cache (LRU strategy).

Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a28677bb60d07d35d925f8d7852e8f142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using Cache&lt; K, V &gt;::const_iterator =  typename std::list&lt;kv_pair&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28677bb60d07d35d925f8d7852e8f142">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> std::list&lt;kv_pair&gt;::const_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#a79258c643559f458b14ecb02a0258d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using Cache&lt; K, V &gt;::iterator =  typename std::list&lt;kv_pair&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79258c643559f458b14ecb02a0258d00">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a79258c643559f458b14ecb02a0258d00">iterator</a>       = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> std::list&lt;kv_pair&gt;::iterator;</span></span></div>

</div>

</div>
</div>

### kv\_pair {#a0378ae0d907403c4e9ae21da645f9331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using Cache&lt; K, V &gt;::kv_pair =  std::pair&lt;K,V&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0378ae0d907403c4e9ae21da645f9331">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a>        = std::pair&lt;K,V&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Cache() {#aaa77900cf0925ea6e46653361bc6be29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cache&lt; K, V &gt;::Cache (size_t capacity)</td>
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

creates a cache that can hold <em>capacity</em> elements

Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa77900cf0925ea6e46653361bc6be29">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaa77900cf0925ea6e46653361bc6be29">Cache</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a62ce1e1112e08368aff14b6627d2d039">capacity</a>) : <a href="#a779e62967f4cc5217b0fdc4158ca4311">m_capacity</a>(<a href="#a62ce1e1112e08368aff14b6627d2d039">capacity</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a62ce1e1112e08368aff14b6627d2d039">Cache&lt; K, V &gt;::capacity</a> and <a href="#a779e62967f4cc5217b0fdc4158ca4311">Cache&lt; K, V &gt;::m\_capacity</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a710ca4c838a720d74a5a9063df23a27e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator Cache&lt; K, V &gt;::begin ()</td>
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



Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a710ca4c838a720d74a5a9063df23a27e">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a79258c643559f458b14ecb02a0258d00">iterator</a> <a href="#a710ca4c838a720d74a5a9063df23a27e">begin</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin();  }</span></span></div>

</div>


Reference <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>.
</div>
</div>

### begin() {#a5212a44b518fd416891d0a0751c8ae78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator Cache&lt; K, V &gt;::begin ()</td>
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



Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5212a44b518fd416891d0a0751c8ae78">158</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a> <a href="#a5212a44b518fd416891d0a0751c8ae78">begin</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.cbegin(); }</span></span></div>

</div>


Reference <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>.
</div>
</div>

### capacity() {#a62ce1e1112e08368aff14b6627d2d039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Cache&lt; K, V &gt;::capacity ()</td>
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

Returns the maximum number of values that can be stored in the cache.

Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62ce1e1112e08368aff14b6627d2d039">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a62ce1e1112e08368aff14b6627d2d039">capacity</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a779e62967f4cc5217b0fdc4158ca4311">m_capacity</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a779e62967f4cc5217b0fdc4158ca4311">Cache&lt; K, V &gt;::m\_capacity</a>.

Referenced by <a href="#aaa77900cf0925ea6e46653361bc6be29">Cache&lt; K, V &gt;::Cache</a>.
</div>
</div>

### clear() {#aaa0c3a5019640bfd305277ac83ff553f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Cache&lt; K, V &gt;::clear ()</td>
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

Clears all values in the cache.

Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa0c3a5019640bfd305277ac83ff553f">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaa0c3a5019640bfd305277ac83ff553f">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a> and <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a>.
</div>
</div>

### end() {#a3328cf128d88cc86cbf81ce38dc81f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator Cache&lt; K, V &gt;::end ()</td>
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



Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3328cf128d88cc86cbf81ce38dc81f0f">157</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a79258c643559f458b14ecb02a0258d00">iterator</a> <a href="#a3328cf128d88cc86cbf81ce38dc81f0f">end</a>()               { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.end();    }</span></span></div>

</div>


Reference <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>.
</div>
</div>

### end() {#a980ba5495fea787d5e88a5f6a24a2f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator Cache&lt; K, V &gt;::end ()</td>
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



Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a980ba5495fea787d5e88a5f6a24a2f4b">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a28677bb60d07d35d925f8d7852e8f142">const_iterator</a> <a href="#a980ba5495fea787d5e88a5f6a24a2f4b">end</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.cend();   }</span></span></div>

</div>


Reference <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>.
</div>
</div>

### find() {#a31d7c56fdd7cf7147e93bbc7b5420901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">V * Cache&lt; K, V &gt;::find (const K &amp; key)</td>
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




Finds a value in the cache given the corresponding <em>key</em>.

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
a pointer to the value or nullptr if the key is not found in the cache
</dd>
</dl>


:::info
The hit and miss counters are updated, see <a href="#ace97657a7c672dcc74d30e43c4006ea7">hits()</a> and <a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">misses()</a>.
:::


Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31d7c56fdd7cf7147e93bbc7b5420901">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    V *<a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> K &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// move the item to the front of the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.splice(<a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">                               it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a848baa79896ab6ebca4433c41b0098a0">m_hits</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// return the value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;it-&gt;second-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">m_misses</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>, <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a>, <a href="#a848baa79896ab6ebca4433c41b0098a0">Cache&lt; K, V &gt;::m\_hits</a> and <a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">Cache&lt; K, V &gt;::m\_misses</a>.
</div>
</div>

### hits() {#ace97657a7c672dcc74d30e43c4006ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Cache&lt; K, V &gt;::hits ()</td>
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

Returns how many of the <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find()</a> calls did find a value in the cache.

Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace97657a7c672dcc74d30e43c4006ea7">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint64_t <a href="#ace97657a7c672dcc74d30e43c4006ea7">hits</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a848baa79896ab6ebca4433c41b0098a0">m_hits</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a848baa79896ab6ebca4433c41b0098a0">Cache&lt; K, V &gt;::m\_hits</a>.
</div>
</div>

### insert() {#a1cf01dfdbe1b56e62c25112e771b23fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">V * Cache&lt; K, V &gt;::insert (const K &amp; key, V &amp;&amp; value)</td>
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

Inserts <em>value</em> under <em>key</em> in the cache.

Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cf01dfdbe1b56e62c25112e771b23fa">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] V *<a href="#a1cf01dfdbe1b56e62c25112e771b23fa">insert</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> K &amp;key,V &amp;&amp;value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// reuse item if it already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// move the item to the front of the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.splice(<a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">                               it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">        std::exchange(it-&gt;second-&gt;second,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;it-&gt;second-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// create new item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.push_front(<a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a>(key,std::move(value)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">      V *result = &amp;<a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.front().second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>[key] = <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove least recently used item if cache is full</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4da60b9993165ac0170ae98b91cd9299">resize</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>, <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a> and <a href="#a4da60b9993165ac0170ae98b91cd9299">Cache&lt; K, V &gt;::resize</a>.
</div>
</div>

### insert() {#a2346678720d2078c031e7ea436e402b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">V * Cache&lt; K, V &gt;::insert (const K &amp; key, const V &amp; value)</td>
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

Inserts <em>value</em> under <em>key</em> in the cache.

Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2346678720d2078c031e7ea436e402b6">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] V *<a href="#a2346678720d2078c031e7ea436e402b6">insert</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> K &amp;key,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> V &amp;value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// reuse item if it already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// move the item to the front of the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.splice(<a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">                               it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;second-&gt;second = value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;it-&gt;second-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// store new item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.push_front(<a href="#a0378ae0d907403c4e9ae21da645f9331">kv_pair</a>(key,value));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      V *result = &amp;<a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.front().second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>[key] = <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove least recently used item if cache is full</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4da60b9993165ac0170ae98b91cd9299">resize</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>, <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a> and <a href="#a4da60b9993165ac0170ae98b91cd9299">Cache&lt; K, V &gt;::resize</a>.
</div>
</div>

### misses() {#aaea59f2a9da7bf4416ed4e2de1c955a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Cache&lt; K, V &gt;::misses ()</td>
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

Returns how many of the <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">find()</a> calls did not found a value in the cache.

Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint64_t <a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">misses</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">m_misses</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">Cache&lt; K, V &gt;::m\_misses</a>.
</div>
</div>

### remove() {#ac3a7d2f92c1e3652b0279dcafe563f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Cache&lt; K, V &gt;::remove (const K &amp; key)</td>
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




Removes entry <em>key</em> from the cache.

:::info
this invalidates any iterators
:::


Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3a7d2f92c1e3652b0279dcafe563f8e">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac3a7d2f92c1e3652b0279dcafe563f8e">remove</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> K &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove item if it already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.erase(it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a> and <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a>.
</div>
</div>

### size() {#a8b8abd9f417e818217ba17f9756f41eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Cache&lt; K, V &gt;::size ()</td>
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

Returns the number of values stored in the cache.

Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b8abd9f417e818217ba17f9756f41eb">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a8b8abd9f417e818217ba17f9756f41eb">size</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### resize() {#a4da60b9993165ac0170ae98b91cd9299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Cache&lt; K, V &gt;::resize ()</td>
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



Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4da60b9993165ac0170ae98b91cd9299">163</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4da60b9993165ac0170ae98b91cd9299">resize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.size() &gt; <a href="#a779e62967f4cc5217b0fdc4158ca4311">m_capacity</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> last_it = <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        --last_it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>.erase(last_it-&gt;first);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a226d4dd4795121ff2915e7363cd97fa5">Cache&lt; K, V &gt;::m\_cacheItemList</a>, <a href="#ac777fc9de9e949a74106b11a9370703c">Cache&lt; K, V &gt;::m\_cacheItemMap</a> and <a href="#a779e62967f4cc5217b0fdc4158ca4311">Cache&lt; K, V &gt;::m\_capacity</a>.

Referenced by <a href="#a2346678720d2078c031e7ea436e402b6">Cache&lt; K, V &gt;::insert</a> and <a href="#a1cf01dfdbe1b56e62c25112e771b23fa">Cache&lt; K, V &gt;::insert</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_cacheItemList {#a226d4dd4795121ff2915e7363cd97fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;kv_pair&gt; Cache&lt; K, V &gt;::m_cacheItemList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a226d4dd4795121ff2915e7363cd97fa5">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::list&lt;kv_pair&gt; <a href="#a226d4dd4795121ff2915e7363cd97fa5">m_cacheItemList</a>;</span></span></div>

</div>


Referenced by <a href="#a710ca4c838a720d74a5a9063df23a27e">Cache&lt; K, V &gt;::begin</a>, <a href="#a5212a44b518fd416891d0a0751c8ae78">Cache&lt; K, V &gt;::begin</a>, <a href="#aaa0c3a5019640bfd305277ac83ff553f">Cache&lt; K, V &gt;::clear</a>, <a href="#a3328cf128d88cc86cbf81ce38dc81f0f">Cache&lt; K, V &gt;::end</a>, <a href="#a980ba5495fea787d5e88a5f6a24a2f4b">Cache&lt; K, V &gt;::end</a>, <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">Cache&lt; K, V &gt;::find</a>, <a href="#a2346678720d2078c031e7ea436e402b6">Cache&lt; K, V &gt;::insert</a>, <a href="#a1cf01dfdbe1b56e62c25112e771b23fa">Cache&lt; K, V &gt;::insert</a>, <a href="#ac3a7d2f92c1e3652b0279dcafe563f8e">Cache&lt; K, V &gt;::remove</a> and <a href="#a4da60b9993165ac0170ae98b91cd9299">Cache&lt; K, V &gt;::resize</a>.
</div>
</div>

### m\_cacheItemMap {#ac777fc9de9e949a74106b11a9370703c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;K,iterator&gt; Cache&lt; K, V &gt;::m_cacheItemMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac777fc9de9e949a74106b11a9370703c">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;K,iterator&gt; <a href="#ac777fc9de9e949a74106b11a9370703c">m_cacheItemMap</a>;</span></span></div>

</div>


Referenced by <a href="#aaa0c3a5019640bfd305277ac83ff553f">Cache&lt; K, V &gt;::clear</a>, <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">Cache&lt; K, V &gt;::find</a>, <a href="#a2346678720d2078c031e7ea436e402b6">Cache&lt; K, V &gt;::insert</a>, <a href="#a1cf01dfdbe1b56e62c25112e771b23fa">Cache&lt; K, V &gt;::insert</a>, <a href="#ac3a7d2f92c1e3652b0279dcafe563f8e">Cache&lt; K, V &gt;::remove</a>, <a href="#a4da60b9993165ac0170ae98b91cd9299">Cache&lt; K, V &gt;::resize</a> and <a href="#a8b8abd9f417e818217ba17f9756f41eb">Cache&lt; K, V &gt;::size</a>.
</div>
</div>

### m\_capacity {#a779e62967f4cc5217b0fdc4158ca4311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Cache&lt; K, V &gt;::m_capacity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a779e62967f4cc5217b0fdc4158ca4311">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a779e62967f4cc5217b0fdc4158ca4311">m_capacity</a>;</span></span></div>

</div>


Referenced by <a href="#aaa77900cf0925ea6e46653361bc6be29">Cache&lt; K, V &gt;::Cache</a>, <a href="#a62ce1e1112e08368aff14b6627d2d039">Cache&lt; K, V &gt;::capacity</a> and <a href="#a4da60b9993165ac0170ae98b91cd9299">Cache&lt; K, V &gt;::resize</a>.
</div>
</div>

### m\_hits {#a848baa79896ab6ebca4433c41b0098a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Cache&lt; K, V &gt;::m_hits =0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a848baa79896ab6ebca4433c41b0098a0">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint64_t <a href="#a848baa79896ab6ebca4433c41b0098a0">m_hits</a>=0;</span></span></div>

</div>


Referenced by <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">Cache&lt; K, V &gt;::find</a> and <a href="#ace97657a7c672dcc74d30e43c4006ea7">Cache&lt; K, V &gt;::hits</a>.
</div>
</div>

### m\_misses {#a16e8b2b3815ee6a0d9a025ee9b3896ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K, typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Cache&lt; K, V &gt;::m_misses =0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint64_t <a href="#a16e8b2b3815ee6a0d9a025ee9b3896ee">m_misses</a>=0;</span></span></div>

</div>


Referenced by <a href="#a31d7c56fdd7cf7147e93bbc7b5420901">Cache&lt; K, V &gt;::find</a> and <a href="#aaea59f2a9da7bf4416ed4e2de1c955a3">Cache&lt; K, V &gt;::misses</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/cache-h">cache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
