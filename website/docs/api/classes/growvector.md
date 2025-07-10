---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/growvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GrowVector` Class Template Reference

<p>std::vector like container optimized for pushing elements to the back. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T&gt;
class GrowVector&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/growvector-h">src/growvector.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a> = <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a>&lt; <a href="/web-doxygen/docs/api/classes/growvector">GrowVector</a>, T &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a> = <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a>&lt; const <a href="/web-doxygen/docs/api/classes/growvector">GrowVector</a>, const T &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae5df7bdd2450792b5d8b625494a28434">ChunkPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/growvector/chunk">Chunk</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6e73da285a472b346e8f26ce4b586ac">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns an iterator to the beginning <a href="#ab6e73da285a472b346e8f26ce4b586ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac248c0617386cc52cbc2bc5d1ab172e1">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns an iterator to the beginning <a href="#ac248c0617386cc52cbc2bc5d1ab172e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26fb83991248fa063b6076dc9b456f10">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns an iterator to the end <a href="#a26fb83991248fa063b6076dc9b456f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a95c3c05d7dfe0c5ec5795c4250262c18">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns an iterator to the end <a href="#a95c3c05d7dfe0c5ec5795c4250262c18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2579ab76c81ca4fa987a413fb4c057d1">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the number of elements <a href="#a2579ab76c81ca4fa987a413fb4c057d1">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24ce2eda38553d4b9ba2956fb37d3397">push_back</a> (T &amp;&amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds an element to the end <a href="#a24ce2eda38553d4b9ba2956fb37d3397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">emplace_back</a> (Args &amp;&amp;...args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>constructs an element in-place at the end <a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47b0fff0a3347fd5134ff7f121511d5f">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the last element <a href="#a47b0fff0a3347fd5134ff7f121511d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a248ca3d1565b83dd4e9a19557eab8e">at</a> (size_t i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access specified element <a href="#a5a248ca3d1565b83dd4e9a19557eab8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">at</a> (size_t i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access specified element <a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad097d3d024ed9fa293f9099352309a25">front</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access the first element <a href="#ad097d3d024ed9fa293f9099352309a25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a31c743f240001ebc7e68fe509b4282">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access the first element <a href="#a3a31c743f240001ebc7e68fe509b4282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32ffacabb2c328729f4e6ead6d96a4ad">back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access the last element <a href="#a32ffacabb2c328729f4e6ead6d96a4ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a661b6fe9802d516bcadc905dba93194f">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>access the last element <a href="#a661b6fe9802d516bcadc905dba93194f">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checks whether the container is empty <a href="#a4e81684f665c9a1a38b5e16cfbe31d41">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a198715b8f95bc34cb020ae11170470f7">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clears the contents <a href="#a198715b8f95bc34cb020ae11170470f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a607b38460ee306c3f66bf27e65f25e">make_room</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="#ae5df7bdd2450792b5d8b625494a28434">ChunkPtr</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static const size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a> = 4</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static const size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a> = 1 &lt;&lt; <a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static const size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe6e97ff69ec6efd6f9daad783ee98c2">chunkMask</a> = <a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a>-1</td>
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

<p>std::vector like container optimized for pushing elements to the back.</p>


<p>It differs from std::vector in that it can grow without invalidating pointers to its members just like std::deque and std::list.</p>


<p>It differs from std::deque in that the value can be incomplete just like std::vector.</p>


<p>It differs from std::list in that it does not need to allocate each node separately and provides random access to its members.</p>


<p>It is implemented as a vector of chunks where each chunk is a fixed capacity vector of T.</p>


<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a3a71f60473fe28d3b8d6725f16ca5de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::const_iterator =  Iterator&lt;const GrowVector,const T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a71f60473fe28d3b8d6725f16ca5de7">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a> = <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator&lt;const GrowVector,const T&gt;</a>;</span></span></div>

</div>

</div>
</div>

### iterator {#a8727be3b562635bcb4edb1ff0c848f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::iterator =  Iterator&lt;GrowVector,T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8727be3b562635bcb4edb1ff0c848f8b">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a>       = <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator&lt;GrowVector,T&gt;</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ChunkPtr {#ae5df7bdd2450792b5d8b625494a28434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::ChunkPtr =  std::unique_ptr&lt;Chunk&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5df7bdd2450792b5d8b625494a28434">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ae5df7bdd2450792b5d8b625494a28434">ChunkPtr</a> = std::unique_ptr&lt;Chunk&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### at() {#a5a248ca3d1565b83dd4e9a19557eab8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; GrowVector&lt; T &gt;::at (size_t i)</td>
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

<p>access specified element</p>

<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a248ca3d1565b83dd4e9a19557eab8e">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">          T &amp;<a href="#a5a248ca3d1565b83dd4e9a19557eab8e">at</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.at(i&gt;&gt;<a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a>)-&gt;data.at(i&amp;<a href="#abe6e97ff69ec6efd6f9daad783ee98c2">chunkMask</a>); }</span></span></div>

</div>


<p>References <a href="#ab5c3a57d662f3663bb79fe3b77787378">GrowVector&lt; T &gt;::chunkBits</a>, <a href="#abe6e97ff69ec6efd6f9daad783ee98c2">GrowVector&lt; T &gt;::chunkMask</a> and <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>

</div>
</div>

### at() {#a15b7d4cd0af1fd8e902d1dab16f14e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; GrowVector&lt; T &gt;::at (size_t i)</td>
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

<p>access specified element</p>

<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;<a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">at</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.at(i&gt;&gt;<a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a>)-&gt;data.at(i&amp;<a href="#abe6e97ff69ec6efd6f9daad783ee98c2">chunkMask</a>); }</span></span></div>

</div>


<p>References <a href="#ab5c3a57d662f3663bb79fe3b77787378">GrowVector&lt; T &gt;::chunkBits</a>, <a href="#abe6e97ff69ec6efd6f9daad783ee98c2">GrowVector&lt; T &gt;::chunkMask</a> and <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>

</div>
</div>

### back() {#a32ffacabb2c328729f4e6ead6d96a4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; GrowVector&lt; T &gt;::back ()</td>
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

<p>access the last element</p>

<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32ffacabb2c328729f4e6ead6d96a4ad">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">          T &amp;<a href="#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.back(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>.</p>

</div>
</div>

### back() {#a661b6fe9802d516bcadc905dba93194f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; GrowVector&lt; T &gt;::back ()</td>
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

<p>access the last element</p>

<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a661b6fe9802d516bcadc905dba93194f">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;<a href="#a661b6fe9802d516bcadc905dba93194f">back</a>()</span><span class="doxyHighlightKeyword"> const       </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.back(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>

</div>
</div>

### begin() {#ab6e73da285a472b346e8f26ce4b586ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator GrowVector&lt; T &gt;::begin ()</td>
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

<p>returns an iterator to the beginning</p>

<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6e73da285a472b346e8f26ce4b586ac">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a> <a href="#ab6e73da285a472b346e8f26ce4b586ac">begin</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a>(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,0); }</span></span></div>

</div>

</div>
</div>

### begin() {#ac248c0617386cc52cbc2bc5d1ab172e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator GrowVector&lt; T &gt;::begin ()</td>
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

<p>returns an iterator to the beginning</p>

<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac248c0617386cc52cbc2bc5d1ab172e1">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a> <a href="#ac248c0617386cc52cbc2bc5d1ab172e1">begin</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a>(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,0); }</span></span></div>

</div>

</div>
</div>

### clear() {#a198715b8f95bc34cb020ae11170470f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowVector&lt; T &gt;::clear ()</td>
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

<p>clears the contents</p>

<p>Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a198715b8f95bc34cb020ae11170470f7">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a198715b8f95bc34cb020ae11170470f7">clear</a>()                { <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.clear(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a> and <a href="/web-doxygen/docs/api/structs/docnodelist/#a6bb13c84c8ad84d77584f6a3ec24a2a9">DocNodeList::move_append</a>.</p>

</div>
</div>

### emplace\_back() {#a7a92b9894590a7470f2f9ebd2d7cda7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowVector&lt; T &gt;::emplace_back (Args &amp;&amp;... args)</td>
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

<p>constructs an element in-place at the end</p>

<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">emplace_back</a>(Args&amp;&amp;...args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3a607b38460ee306c3f66bf27e65f25e">make_room</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.emplace_back(std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a> and <a href="#a3a607b38460ee306c3f66bf27e65f25e">GrowVector&lt; T &gt;::make_room</a>.</p>

</div>
</div>

### empty() {#a4e81684f665c9a1a38b5e16cfbe31d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GrowVector&lt; T &gt;::empty ()</td>
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

<p>checks whether the container is empty</p>

<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e81684f665c9a1a38b5e16cfbe31d41">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.empty(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">DocImage::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow/#a2c68c88e4d8b744c79fbee1936aaf0c2">DocVhdlFlow::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#ae27763e0e3579fbd9d2d67e7fbebda47">DocTitle::hasTitle</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a004ec58b69c71d43ebf4424b04dc5779">DocPara::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docroot/#ade1a2bc91120fb42b66313298b37199d">DocRoot::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/doctext/#adeed56e5d1701811126f1bd221412ef2">DocText::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2ef300f18d17dba697499319c88c8eb7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a104c3ca52ddda7596a073155996e8214">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a3ad488448307ccde3303915e92c56a69">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4ff7d5a66db3412ce103eeb44fee565c">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>.</p>

</div>
</div>

### end() {#a26fb83991248fa063b6076dc9b456f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator GrowVector&lt; T &gt;::end ()</td>
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

<p>returns an iterator to the end</p>

<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26fb83991248fa063b6076dc9b456f10">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a> <a href="#a26fb83991248fa063b6076dc9b456f10">end</a>()               { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8727be3b562635bcb4edb1ff0c848f8b">iterator</a>(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="#a2579ab76c81ca4fa987a413fb4c057d1">size</a>()); }</span></span></div>

</div>


<p>Reference <a href="#a2579ab76c81ca4fa987a413fb4c057d1">GrowVector&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>.</p>

</div>
</div>

### end() {#a95c3c05d7dfe0c5ec5795c4250262c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator GrowVector&lt; T &gt;::end ()</td>
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

<p>returns an iterator to the end</p>

<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a95c3c05d7dfe0c5ec5795c4250262c18">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a> <a href="#a95c3c05d7dfe0c5ec5795c4250262c18">end</a>()</span><span class="doxyHighlightKeyword">   const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3a71f60473fe28d3b8d6725f16ca5de7">const_iterator</a>(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="#a2579ab76c81ca4fa987a413fb4c057d1">size</a>()); }</span></span></div>

</div>


<p>Reference <a href="#a2579ab76c81ca4fa987a413fb4c057d1">GrowVector&lt; T &gt;::size</a>.</p>

</div>
</div>

### front() {#ad097d3d024ed9fa293f9099352309a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; GrowVector&lt; T &gt;::front ()</td>
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

<p>access the first element</p>

<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad097d3d024ed9fa293f9099352309a25">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">          T &amp;<a href="#ad097d3d024ed9fa293f9099352309a25">front</a>()            { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.front()-&gt;data.front(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dochtmltable/#afc50242564e265147b101926f1efce5e">DocHtmlTable::firstRow</a> and <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab3dc4aca49387c2801b733951162e52c">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

### front() {#a3a31c743f240001ebc7e68fe509b4282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; GrowVector&lt; T &gt;::front ()</td>
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

<p>access the first element</p>

<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a31c743f240001ebc7e68fe509b4282">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;<a href="#a3a31c743f240001ebc7e68fe509b4282">front</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.front()-&gt;data.front(); }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>

</div>
</div>

### pop\_back() {#a47b0fff0a3347fd5134ff7f121511d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowVector&lt; T &gt;::pop_back ()</td>
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

<p>removes the last element</p>

<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47b0fff0a3347fd5134ff7f121511d5f">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a47b0fff0a3347fd5134ff7f121511d5f">pop_back</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.size()==0) </span><span class="doxyHighlightComment">// remove chunk if empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a> and <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>.</p>

</div>
</div>

### push\_back() {#a24ce2eda38553d4b9ba2956fb37d3397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowVector&lt; T &gt;::push_back (T &amp;&amp; t)</td>
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

<p>adds an element to the end</p>

<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24ce2eda38553d4b9ba2956fb37d3397">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24ce2eda38553d4b9ba2956fb37d3397">push_back</a>(T &amp;&amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3a607b38460ee306c3f66bf27e65f25e">make_room</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.push_back(std::move(t));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a> and <a href="#a3a607b38460ee306c3f66bf27e65f25e">GrowVector&lt; T &gt;::make_room</a>.</p>

</div>
</div>

### size() {#a2579ab76c81ca4fa987a413fb4c057d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GrowVector&lt; T &gt;::size ()</td>
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

<p>returns the number of elements</p>

<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2579ab76c81ca4fa987a413fb4c057d1">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a2579ab76c81ca4fa987a413fb4c057d1">size</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.empty() ? 0 : (<a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.size()-1)*<a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a47759ca4db6dd81e364fea79107c9749">GrowVector&lt; T &gt;::chunkSize</a> and <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="#a26fb83991248fa063b6076dc9b456f10">GrowVector&lt; T &gt;::end</a>, <a href="#a95c3c05d7dfe0c5ec5795c4250262c18">GrowVector&lt; T &gt;::end</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac8411351d60c38dd457f0d118b1a3ab3">DocHtmlRow::numCells</a> and <a href="/web-doxygen/docs/api/classes/dochtmltable/#a197727d94413c8a39461bb9008d57390">DocHtmlTable::numRows</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### make\_room() {#a3a607b38460ee306c3f66bf27e65f25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowVector&lt; T &gt;::make_room ()</td>
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



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a607b38460ee306c3f66bf27e65f25e">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a607b38460ee306c3f66bf27e65f25e">make_room</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.empty() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.back()-&gt;data.size()==<a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a>) </span><span class="doxyHighlightComment">// add new chuck if needed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>.push_back(std::make_unique&lt;Chunk&gt;());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a47759ca4db6dd81e364fea79107c9749">GrowVector&lt; T &gt;::chunkSize</a> and <a href="#aa61eea0024352265278288084cb02cd3">GrowVector&lt; T &gt;::m_chunks</a>.</p>


<p>Referenced by <a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">GrowVector&lt; T &gt;::emplace_back</a> and <a href="#a24ce2eda38553d4b9ba2956fb37d3397">GrowVector&lt; T &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_chunks {#aa61eea0024352265278288084cb02cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChunkPtr&gt; GrowVector&lt; T &gt;::m_chunks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa61eea0024352265278288084cb02cd3">154</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;ChunkPtr&gt; <a href="#aa61eea0024352265278288084cb02cd3">m_chunks</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5a248ca3d1565b83dd4e9a19557eab8e">GrowVector&lt; T &gt;::at</a>, <a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">GrowVector&lt; T &gt;::at</a>, <a href="#a32ffacabb2c328729f4e6ead6d96a4ad">GrowVector&lt; T &gt;::back</a>, <a href="#a661b6fe9802d516bcadc905dba93194f">GrowVector&lt; T &gt;::back</a>, <a href="#a198715b8f95bc34cb020ae11170470f7">GrowVector&lt; T &gt;::clear</a>, <a href="#a7a92b9894590a7470f2f9ebd2d7cda7b">GrowVector&lt; T &gt;::emplace_back</a>, <a href="#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="#ad097d3d024ed9fa293f9099352309a25">GrowVector&lt; T &gt;::front</a>, <a href="#a3a31c743f240001ebc7e68fe509b4282">GrowVector&lt; T &gt;::front</a>, <a href="#a3a607b38460ee306c3f66bf27e65f25e">GrowVector&lt; T &gt;::make_room</a>, <a href="#a47b0fff0a3347fd5134ff7f121511d5f">GrowVector&lt; T &gt;::pop_back</a>, <a href="#a24ce2eda38553d4b9ba2956fb37d3397">GrowVector&lt; T &gt;::push_back</a> and <a href="#a2579ab76c81ca4fa987a413fb4c057d1">GrowVector&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### chunkBits {#ab5c3a57d662f3663bb79fe3b77787378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t GrowVector&lt; T &gt;::chunkBits = 4</td>
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



<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5c3a57d662f3663bb79fe3b77787378">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a> = 4; </span><span class="doxyHighlightComment">// a chunk holds 2^bits elements</span></span></div>

</div>


<p>Referenced by <a href="#a5a248ca3d1565b83dd4e9a19557eab8e">GrowVector&lt; T &gt;::at</a> and <a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">GrowVector&lt; T &gt;::at</a>.</p>

</div>
</div>

### chunkMask {#abe6e97ff69ec6efd6f9daad783ee98c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t GrowVector&lt; T &gt;::chunkMask = <a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a>-1</td>
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



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe6e97ff69ec6efd6f9daad783ee98c2">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#abe6e97ff69ec6efd6f9daad783ee98c2">chunkMask</a> = <a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a>-1;</span></span></div>

</div>


<p>Referenced by <a href="#a5a248ca3d1565b83dd4e9a19557eab8e">GrowVector&lt; T &gt;::at</a> and <a href="#a15b7d4cd0af1fd8e902d1dab16f14e23">GrowVector&lt; T &gt;::at</a>.</p>

</div>
</div>

### chunkSize {#a47759ca4db6dd81e364fea79107c9749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t GrowVector&lt; T &gt;::chunkSize = 1 &lt;&lt; <a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a></td>
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



<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47759ca4db6dd81e364fea79107c9749">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a47759ca4db6dd81e364fea79107c9749">chunkSize</a> = 1 &lt;&lt; <a href="#ab5c3a57d662f3663bb79fe3b77787378">chunkBits</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/growvector/chunk/#a7920149181815d91225b896d6a9cd9d5">GrowVector&lt; T &gt;::Chunk::Chunk</a>, <a href="#a3a607b38460ee306c3f66bf27e65f25e">GrowVector&lt; T &gt;::make_room</a> and <a href="#a2579ab76c81ca4fa987a413fb4c057d1">GrowVector&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
