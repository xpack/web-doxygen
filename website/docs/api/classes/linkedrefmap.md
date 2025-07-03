---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/linkedrefmap
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LinkedRefMap` Class Template Reference

<p>Container class representing a vector of objects with keys. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;
class LinkedRefMap&lt;T, Hash, KeyEqual, Map&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/linkedmap-h">src/linkedmap.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> = T *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae57b9ddb3cac6283df8b9747dff2e1da">Vec</a> = std::vector&lt; <a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a> = typename Vec::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a> = typename Vec::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a> = typename Vec::reverse_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a> = typename Vec::const_reverse_iterator</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89581f93afd0740dee45e136d1a54546">operator[]</a> (size_t pos)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09d227163284233b8e37f3a265510b49">operator[]</a> (size_t pos) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a> (const std::string &amp;key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d3f8cefe5cfd6d46e95889817b92140">find</a> (const QCString &amp;key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed765c5f6f6956643f0753c9ea1d714e">find</a> (const char *key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e393b31c768a9de5d04455a8596e1a9">find</a> (const char *key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>non-const wrapper for find() const <a href="#a0e393b31c768a9de5d04455a8596e1a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f413af4720b2f575c911b78ee3a70b1">find</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6dab86c77d6037d5fc0be82fca6e1587">find</a> (const std::string &amp;key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>non-const wrapper for find() const <a href="#a6dab86c77d6037d5fc0be82fca6e1587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a273fe87b60116a378346a858e11e4b6e">add</a> (const char *k, T *obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acaf21f8a88dc994cf1de14246e679579">add</a> (const QCString &amp;k, T *obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a821db7bc14f1498938bd5314502f3655">prepend</a> (const char *k, T *obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98b0589fd4091da2efa1c5ee2da43f73">prepend</a> (const QCString &amp;key, T *obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5fad70772de2ff561c5883f5a8919c5d">del</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2f30ce85fd85bfb75bcb56bd10fe9a4">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d843d470df85d608d8d47b2a56c5e80">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77a3307eb17ea829836140639cb52115">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fed959ab40da898bbebfdb3c8653b2c">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac971d2e3cc8e2651f5648b6946b25bd7">rbegin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a306a67c71e29179b309647309d6e96">rend</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d088d23b0ce73cf2ed3b8cfc2fbe89d">rbegin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab67fb1418120d42cf91a2a033a6b16ad">rend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4eea714e29d412612981ac2a8bcab40">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5fe0b41a59bcf683e2ade44911a3fe1d">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad67fa2110f306614b020782b88c28c83">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Map</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae57b9ddb3cac6283df8b9747dff2e1da">Vec</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a></td>
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

<p>Container class representing a vector of objects with keys.</p>


<p>Objects can be efficiently be looked up given the key. Objects are <em>not</em> owned by the container, the container will only hold references. When adding objects the order of addition is kept, and used while iterating.</p>


<p>Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ae9d600d6dc898d3efd063381f60eaaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::const_iterator =  typename Vec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9d600d6dc898d3efd063381f60eaaf7">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_iterator;</span></span></div>

</div>

</div>
</div>

### const\_reverse\_iterator {#a5d04d68baaeb769cfe0e3cfa9873e40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::const_reverse_iterator =  typename Vec::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_reverse_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#aee7c1420984bc5d41ef945689343be5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee7c1420984bc5d41ef945689343be5c">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Ptr {#a9db9596845180652ad8b36774d6d9b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::Ptr =  T*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9db9596845180652ad8b36774d6d9b30">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> = T*;</span></span></div>

</div>

</div>
</div>

### reverse\_iterator {#a7c63027ad3bccd9ba3a87b2818ecf12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::reverse_iterator =  typename Vec::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::reverse_iterator;</span></span></div>

</div>

</div>
</div>

### Vec {#ae57b9ddb3cac6283df8b9747dff2e1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::Vec =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae57b9ddb3cac6283df8b9747dff2e1da">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ae57b9ddb3cac6283df8b9747dff2e1da">Vec</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a89581f93afd0740dee45e136d1a54546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ptr &amp; LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::operator[] (size_t pos)</td>
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



<p>Definition at line 364 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89581f93afd0740dee45e136d1a54546">364</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> &amp;<a href="#a89581f93afd0740dee45e136d1a54546">operator[]</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>[pos];      }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### operator\[\]() {#a09d227163284233b8e37f3a265510b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ptr &amp; LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::operator[] (size_t pos)</td>
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



<p>Definition at line 365 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09d227163284233b8e37f3a265510b49">365</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a9db9596845180652ad8b36774d6d9b30">Ptr</a> &amp;<a href="#a09d227163284233b8e37f3a265510b49">operator[]</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>[pos];      }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a273fe87b60116a378346a858e11e4b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add (const char * k, T * obj)</td>
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




<p>Adds an object reference to the ordered vector if it was not added already. Return true if the reference was added, and false if an object with the same key was already added before</p>


<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a273fe87b60116a378346a858e11e4b6e">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a273fe87b60116a378346a858e11e4b6e">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *k, T* obj)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(k)==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// new element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string key(k ? k : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.emplace(key,obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.push_back(obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// already existing, don't add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a4aec37ad5da49941a8993835db185ab8">FileDefImpl::insertClass</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a37dc5ed59ff43edea5cae22046984986">NamespaceDefImpl::insertClass</a>.</p>

</div>
</div>

### add() {#acaf21f8a88dc994cf1de14246e679579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; k, T * obj)</td>
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



<p>Definition at line 299 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acaf21f8a88dc994cf1de14246e679579">299</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acaf21f8a88dc994cf1de14246e679579">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;k, T* obj)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key = k.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(key)==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// new element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.emplace(key,obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.push_back(obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// already existing, don't add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### begin() {#ac2f30ce85fd85bfb75bcb56bd10fe9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::begin ()</td>
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



<p>Definition at line 366 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2f30ce85fd85bfb75bcb56bd10fe9a4">366</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a> <a href="#ac2f30ce85fd85bfb75bcb56bd10fe9a4">begin</a>()                        { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.begin();   }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### begin() {#a77a3307eb17ea829836140639cb52115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::begin ()</td>
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



<p>Definition at line 368 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77a3307eb17ea829836140639cb52115">368</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a> <a href="#a77a3307eb17ea829836140639cb52115">begin</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.cbegin();  }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### clear() {#ad67fa2110f306614b020782b88c28c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::clear ()</td>
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



<p>Definition at line 377 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad67fa2110f306614b020782b88c28c83">377</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad67fa2110f306614b020782b88c28c83">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>

</div>
</div>

### del() {#a5fad70772de2ff561c5883f5a8919c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::del (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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




<p>Removes an object from the container and deletes it. Returns true if the object was deleted or false it is was not found.</p>


<p>Definition at line 348 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fad70772de2ff561c5883f5a8919c5d">348</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5fad70772de2ff561c5883f5a8919c5d">del</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> vecit = std::find_if(<a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.begin(),<a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.end(),[obj=it-&gt;second](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;el) { return el.get()==obj; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (vecit!=<a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.end()) </span><span class="doxyHighlightComment">// should always be true</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.erase(vecit);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### empty() {#ad4eea714e29d412612981ac2a8bcab40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::empty ()</td>
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



<p>Definition at line 374 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad4eea714e29d412612981ac2a8bcab40">374</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad4eea714e29d412612981ac2a8bcab40">empty</a>()</span><span class="doxyHighlightKeyword"> const                      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.empty();   }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.</p>

</div>
</div>

### end() {#a7d843d470df85d608d8d47b2a56c5e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::end ()</td>
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



<p>Definition at line 367 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d843d470df85d608d8d47b2a56c5e80">367</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aee7c1420984bc5d41ef945689343be5c">iterator</a> <a href="#a7d843d470df85d608d8d47b2a56c5e80">end</a>()                          { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.end();     }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### end() {#a6fed959ab40da898bbebfdb3c8653b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::end ()</td>
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



<p>Definition at line 369 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fed959ab40da898bbebfdb3c8653b2c">369</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae9d600d6dc898d3efd063381f60eaaf7">const_iterator</a> <a href="#a6fed959ab40da898bbebfdb3c8653b2c">end</a>()</span><span class="doxyHighlightKeyword"> const              </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.cend();    }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### find() {#a9f6506fe8d15e7f43f61929560a3c377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const std::string &amp; key)</td>
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




<p>find an object given the key. Returns a pointer to the object if found or nullptr if it is not found.</p>


<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f6506fe8d15e7f43f61929560a3c377">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>


<p>Referenced by <a href="#a273fe87b60116a378346a858e11e4b6e">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#acaf21f8a88dc994cf1de14246e679579">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a0e393b31c768a9de5d04455a8596e1a9">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#aed765c5f6f6956643f0753c9ea1d714e">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a2f413af4720b2f575c911b78ee3a70b1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6dab86c77d6037d5fc0be82fca6e1587">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="#a821db7bc14f1498938bd5314502f3655">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a> and <a href="#a98b0589fd4091da2efa1c5ee2da43f73">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>.</p>

</div>
</div>

### find() {#a3d3f8cefe5cfd6d46e95889817b92140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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




<p>find an object given the key. Returns a pointer to the object if found or nullptr if it is not found.</p>


<p>Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d3f8cefe5cfd6d46e95889817b92140">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#a3d3f8cefe5cfd6d46e95889817b92140">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### find() {#aed765c5f6f6956643f0753c9ea1d714e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const char * key)</td>
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




<p>find an object given the key. Returns a pointer to the object if found or nullptr if it is not found.</p>


<p>Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed765c5f6f6956643f0753c9ea1d714e">259</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#aed765c5f6f6956643f0753c9ea1d714e">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(std::string(key ? key : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a0e393b31c768a9de5d04455a8596e1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const char * key)</td>
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

<p>non-const wrapper for find() const</p>

<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e393b31c768a9de5d04455a8596e1a9">265</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a0e393b31c768a9de5d04455a8596e1a9">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a2f413af4720b2f575c911b78ee3a70b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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



<p>Definition at line 270 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f413af4720b2f575c911b78ee3a70b1">270</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a2f413af4720b2f575c911b78ee3a70b1">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a6dab86c77d6037d5fc0be82fca6e1587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find (const std::string &amp; key)</td>
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

<p>non-const wrapper for find() const</p>

<p>Definition at line 276 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6dab86c77d6037d5fc0be82fca6e1587">276</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a6dab86c77d6037d5fc0be82fca6e1587">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### prepend() {#a821db7bc14f1498938bd5314502f3655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend (const char * k, T * obj)</td>
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




<p>Prepends an object reference to the ordered vector if it was not added already. Return true if the reference was added, and false if an object with the same key was already added before</p>


<p>Definition at line 317 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a821db7bc14f1498938bd5314502f3655">317</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a821db7bc14f1498938bd5314502f3655">prepend</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *k, T* obj)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(k)==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// new element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string key(k ? k : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.emplace(key,obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.insert(<a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.begin(),obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// already existing, don't add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>

</div>
</div>

### prepend() {#a98b0589fd4091da2efa1c5ee2da43f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key, T * obj)</td>
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



<p>Definition at line 332 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98b0589fd4091da2efa1c5ee2da43f73">332</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a98b0589fd4091da2efa1c5ee2da43f73">prepend</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key, T* obj)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9f6506fe8d15e7f43f61929560a3c377">find</a>(key)==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// new element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>.emplace(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.insert(<a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.begin(),obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// already existing, don't add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#aa825d33ecc2a6b96492886f163b7d47a">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### rbegin() {#ac971d2e3cc8e2651f5648b6946b25bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin ()</td>
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



<p>Definition at line 370 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac971d2e3cc8e2651f5648b6946b25bd7">370</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a> <a href="#ac971d2e3cc8e2651f5648b6946b25bd7">rbegin</a>()               { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.rbegin();  }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rbegin() {#a2d088d23b0ce73cf2ed3b8cfc2fbe89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin ()</td>
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



<p>Definition at line 372 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d088d23b0ce73cf2ed3b8cfc2fbe89d">372</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a> <a href="#a2d088d23b0ce73cf2ed3b8cfc2fbe89d">rbegin</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.crbegin(); }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rend() {#a2a306a67c71e29179b309647309d6e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rend ()</td>
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



<p>Definition at line 371 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a306a67c71e29179b309647309d6e96">371</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7c63027ad3bccd9ba3a87b2818ecf12a">reverse_iterator</a> <a href="#a2a306a67c71e29179b309647309d6e96">rend</a>()                 { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.rend();    }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rend() {#ab67fb1418120d42cf91a2a033a6b16ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rend ()</td>
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



<p>Definition at line 373 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab67fb1418120d42cf91a2a033a6b16ad">373</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5d04d68baaeb769cfe0e3cfa9873e40f">const_reverse_iterator</a> <a href="#ab67fb1418120d42cf91a2a033a6b16ad">rend</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.crend();   }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### size() {#a5fe0b41a59bcf683e2ade44911a3fe1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::size ()</td>
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



<p>Definition at line 375 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fe0b41a59bcf683e2ade44911a3fe1d">375</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a5fe0b41a59bcf683e2ade44911a3fe1d">size</a>()</span><span class="doxyHighlightKeyword"> const                     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>.size();    }</span></span></div>

</div>


<p>Reference <a href="#a1ad918f78e81ed4580bcd9c0654fced1">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_entries {#a1ad918f78e81ed4580bcd9c0654fced1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ad918f78e81ed4580bcd9c0654fced1">385</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae57b9ddb3cac6283df8b9747dff2e1da">Vec</a> <a href="#a1ad918f78e81ed4580bcd9c0654fced1">m_entries</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a273fe87b60116a378346a858e11e4b6e">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#acaf21f8a88dc994cf1de14246e679579">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#ac2f30ce85fd85bfb75bcb56bd10fe9a4">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::begin</a>, <a href="#a77a3307eb17ea829836140639cb52115">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::begin</a>, <a href="#ad67fa2110f306614b020782b88c28c83">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::clear</a>, <a href="#a5fad70772de2ff561c5883f5a8919c5d">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="#ad4eea714e29d412612981ac2a8bcab40">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::empty</a>, <a href="#a7d843d470df85d608d8d47b2a56c5e80">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::end</a>, <a href="#a6fed959ab40da898bbebfdb3c8653b2c">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::end</a>, <a href="#a89581f93afd0740dee45e136d1a54546">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::operator[]</a>, <a href="#a09d227163284233b8e37f3a265510b49">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::operator[]</a>, <a href="#a821db7bc14f1498938bd5314502f3655">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="#a98b0589fd4091da2efa1c5ee2da43f73">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="#ac971d2e3cc8e2651f5648b6946b25bd7">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin</a>, <a href="#a2d088d23b0ce73cf2ed3b8cfc2fbe89d">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin</a>, <a href="#a2a306a67c71e29179b309647309d6e96">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rend</a>, <a href="#ab67fb1418120d42cf91a2a033a6b16ad">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::rend</a> and <a href="#a5fe0b41a59bcf683e2ade44911a3fe1d">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::size</a>.</p>

</div>
</div>

### m\_lookup {#aa825d33ecc2a6b96492886f163b7d47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Map LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa825d33ecc2a6b96492886f163b7d47a">384</a></span><span class="doxyLineContent"><span class="doxyHighlight">    Map <a href="#aa825d33ecc2a6b96492886f163b7d47a">m_lookup</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a273fe87b60116a378346a858e11e4b6e">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#acaf21f8a88dc994cf1de14246e679579">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#ad67fa2110f306614b020782b88c28c83">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::clear</a>, <a href="#a5fad70772de2ff561c5883f5a8919c5d">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="#a3d3f8cefe5cfd6d46e95889817b92140">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a9f6506fe8d15e7f43f61929560a3c377">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a821db7bc14f1498938bd5314502f3655">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a> and <a href="#a98b0589fd4091da2efa1c5ee2da43f73">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
