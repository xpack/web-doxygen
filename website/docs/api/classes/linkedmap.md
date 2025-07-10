---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/linkedmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LinkedMap` Class Template Reference

<p>Container class representing a vector of objects with keys. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;
class LinkedMap&lt;T, Hash, KeyEqual, Map&gt; { ... }
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> = std::unique_ptr&lt; T &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4cfcf6ff5a2f4c0cb16d52eded44146">Vec</a> = std::vector&lt; <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a> = typename Vec::iterator</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a> = typename Vec::const_iterator</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a> = typename Vec::reverse_iterator</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a> = typename Vec::const_reverse_iterator</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf2840eabd548e287a9db8c40d453eb2">operator[]</a> (size_t pos)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58e9cb2ea5649b464cd9a34f58ace816">operator[]</a> (size_t pos) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7659775b7de962b4fe0921456baf4f4">find</a> (const std::string &amp;key) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa43fff2a2b489b77245b73478b391136">find</a> (const QCString &amp;key) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed32ef99019918a4c854c58e3fa4f918">find</a> (const char *key) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a658afbac162b60faccc48da30fc39470">find</a> (const char *key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A non-const wrapper for find() const. <a href="#a658afbac162b60faccc48da30fc39470">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8049d249bddabf8b19862a1013c151da">find</a> (const QCString &amp;key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A non-const wrapper for find() const. <a href="#a8049d249bddabf8b19862a1013c151da">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22821349a515cf453414cd64dc5bd750">find</a> (const std::string &amp;key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A non-const wrapper for find() const. <a href="#a22821349a515cf453414cd64dc5bd750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acddca8cb09f114936f6b80276f2c9c1b">add</a> (const char *k, Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32a09a931c866f27807ceeabb48946f4">add</a> (const QCString &amp;k, Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addab86ba882be1f9c4137b6ceb095991">add</a> (const char *k, Ptr &amp;&amp;ptr)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0ee1991e602ebd106de0fe5884979b6">add</a> (const QCString &amp;k, Ptr &amp;&amp;ptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5e00dabde23084cd671b0fe61772297">prepend</a> (const char *k, Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f76d619b8096fc4446808b378b8ce14">prepend</a> (const QCString &amp;key, Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6150feb21a667df3826df38c1a0878fa">del</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f9f85656f6481dc10277057d168d74e">begin</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5583f9f11e470f5810a431a795f64d2">end</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a97730addaf4399cae4511cea404a482b">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae54a6938e3c17da11dd1d23a6217499d">end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca527abc73458116bb7c965a4417ab42">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a833c562ee3244c51c48acb2284e56f89">rend</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7bb388567d79b9d1e97198cdde6c3f0">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa92f5f3a31fd45d04e4bb38e04112f5b">rend</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a1da7be0df75c8ef81cdb3d825c6df3">empty</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1237f7ce32427ef9f9f334d0b97b1fb">size</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a607048cb06f6ad98ae763d5734db73d4">clear</a> ()</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac4cfcf6ff5a2f4c0cb16d52eded44146">Vec</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a></td>
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


<p>Objects can efficiently be looked up given the key. Objects are owned by the container. When adding objects the order of addition is kept, and used while iterating.</p>


<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a761eb01323123cf737f88cf65adaa95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::const_iterator =  typename Vec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a761eb01323123cf737f88cf65adaa95d">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_iterator;</span></span></div>

</div>

</div>
</div>

### const\_reverse\_iterator {#addcb5d41602952016038d8315e183d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::const_reverse_iterator =  typename Vec::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#addcb5d41602952016038d8315e183d49">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_reverse_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#a972c395a37e958118752ebda8c7ec6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a972c395a37e958118752ebda8c7ec6d3">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Ptr {#a73e8a4070e6a4399bde615098e2b074d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::Ptr =  std::unique_ptr&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73e8a4070e6a4399bde615098e2b074d">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> = std::unique_ptr&lt;T&gt;;</span></span></div>

</div>

</div>
</div>

### reverse\_iterator {#a3f1e6d91dde39b1a948a67f401a5afaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::reverse_iterator =  typename Vec::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f1e6d91dde39b1a948a67f401a5afaa">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::reverse_iterator;</span></span></div>

</div>

</div>
</div>

### Vec {#ac4cfcf6ff5a2f4c0cb16d52eded44146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::Vec =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4cfcf6ff5a2f4c0cb16d52eded44146">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ac4cfcf6ff5a2f4c0cb16d52eded44146">Vec</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#adf2840eabd548e287a9db8c40d453eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ptr &amp; LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::operator[] (size_t pos)</td>
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



<p>Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf2840eabd548e287a9db8c40d453eb2">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;<a href="#adf2840eabd548e287a9db8c40d453eb2">operator[]</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>[pos];      }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### operator\[\]() {#a58e9cb2ea5649b464cd9a34f58ace816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ptr &amp; LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::operator[] (size_t pos)</td>
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



<p>Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a58e9cb2ea5649b464cd9a34f58ace816">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;<a href="#a58e9cb2ea5649b464cd9a34f58ace816">operator[]</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>[pos];      }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#acddca8cb09f114936f6b80276f2c9c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add (const char * k, Args &amp;&amp;... args)</td>
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




<p>Adds a new object to the ordered vector if it was not added already. Return a non-owning pointer to the newly added object, or to the existing object if it was already inserted before under the given key.</p>


<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acddca8cb09f114936f6b80276f2c9c1b">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] T *<a href="#acddca8cb09f114936f6b80276f2c9c1b">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *k, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(k);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string key(k ? k : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> ptr = std::make_unique&lt;T&gt;(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(k),std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_back(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/sectionmanager/#a320fc1c937898dd004caadd235e6d68a">SectionManager::add</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afbb62a940b1b5d7dda3b31a81a9df922">SectionManager::add</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab1c5d97fd966b1d6996e5c4ce21c88b1">readDir</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfb0efa72e3e5ed08b1881ccd8332e5e">readFileOrDirectory</a> and <a href="/web-doxygen/docs/api/classes/sectionmanager/#aa01b0cef766ad1df71b59741da1d7d88">SectionManager::replace</a>.</p>

</div>
</div>

### add() {#a32a09a931c866f27807ceeabb48946f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; k, Args &amp;&amp;... args)</td>
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



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32a09a931c866f27807ceeabb48946f4">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] T *<a href="#a32a09a931c866f27807ceeabb48946f4">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;k, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key = k.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> ptr = std::make_unique&lt;T&gt;(k,std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_back(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### add() {#addab86ba882be1f9c4137b6ceb095991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add (const char * k, <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;&amp; ptr)</td>
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




<p>Adds an existing object to the ordered vector (unless another object was already added under the same key). Ownership is transferred. Return a non-owning pointer to the newly added object, or to the existing object if it was already inserted before under the given key.</p>


<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#addab86ba882be1f9c4137b6ceb095991">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] T *<a href="#addab86ba882be1f9c4137b6ceb095991">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *k, <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;&amp;ptr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(k);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string key(k ? k : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_back(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>

</div>
</div>

### add() {#ab0ee1991e602ebd106de0fe5884979b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; k, <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;&amp; ptr)</td>
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



<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0ee1991e602ebd106de0fe5884979b6">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    [[maybe_unused]] T *<a href="#ab0ee1991e602ebd106de0fe5884979b6">add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;k, <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> &amp;&amp;ptr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key = k.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_back(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### begin() {#a4f9f85656f6481dc10277057d168d74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::begin ()</td>
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



<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f9f85656f6481dc10277057d168d74e">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a> <a href="#a4f9f85656f6481dc10277057d168d74e">begin</a>()                        { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.begin();   }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### begin() {#a97730addaf4399cae4511cea404a482b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::begin ()</td>
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



<p>Definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97730addaf4399cae4511cea404a482b">203</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a> <a href="#a97730addaf4399cae4511cea404a482b">begin</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.cbegin();  }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### clear() {#a607048cb06f6ad98ae763d5734db73d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::clear ()</td>
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



<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a607048cb06f6ad98ae763d5734db73d4">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a607048cb06f6ad98ae763d5734db73d4">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a798729dca95209ecdc609807a653a2bf">clearAll</a>.</p>

</div>
</div>

### del() {#a6150feb21a667df3826df38c1a0878fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::del (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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


<p>Definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6150feb21a667df3826df38c1a0878fa">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6150feb21a667df3826df38c1a0878fa">del</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> vecit = std::find_if(<a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.begin(),<a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.end(),[obj=it-&gt;second](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;el) { return el.get()==obj; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (vecit!=<a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.end()) </span><span class="doxyHighlightComment">// should always be true</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.erase(vecit);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>.</p>

</div>
</div>

### empty() {#a9a1da7be0df75c8ef81cdb3d825c6df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::empty ()</td>
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



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a1da7be0df75c8ef81cdb3d825c6df3">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9a1da7be0df75c8ef81cdb3d825c6df3">empty</a>()</span><span class="doxyHighlightKeyword"> const                      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.empty();   }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### end() {#aa5583f9f11e470f5810a431a795f64d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::end ()</td>
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



<p>Definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5583f9f11e470f5810a431a795f64d2">202</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a972c395a37e958118752ebda8c7ec6d3">iterator</a> <a href="#aa5583f9f11e470f5810a431a795f64d2">end</a>()                          { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.end();     }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### end() {#ae54a6938e3c17da11dd1d23a6217499d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::end ()</td>
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



<p>Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae54a6938e3c17da11dd1d23a6217499d">204</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a761eb01323123cf737f88cf65adaa95d">const_iterator</a> <a href="#ae54a6938e3c17da11dd1d23a6217499d">end</a>()</span><span class="doxyHighlightKeyword"> const              </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.cend();    }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### find() {#ad7659775b7de962b4fe0921456baf4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const std::string &amp; key)</td>
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




<p>Find an object given the key. Returns a pointer to the element if found or nullptr if it is not found.</p>


<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7659775b7de962b4fe0921456baf4f4">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>


<p>Referenced by <a href="#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#addab86ba882be1f9c4137b6ceb095991">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a32a09a931c866f27807ceeabb48946f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#ab0ee1991e602ebd106de0fe5884979b6">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8111356e211d82aed6baea53cda91872">addAnchor</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af9360a554b5e9b817c991a39445e2b39">addSection</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a3aae8d1912d3c3491c992ea5d60fd9d5">DefinitionImpl::addSectionsToDefinition</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#a7dbcc0b3d8792f7eb24a5586609bd020">DocAnchor::DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a26024c34c8fc5cbe9ba0d57218e17f1f">DocHtmlCaption::DocHtmlCaption</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="#a658afbac162b60faccc48da30fc39470">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#aed32ef99019918a4c854c58e3fa4f918">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a8049d249bddabf8b19862a1013c151da">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a22821349a515cf453414cd64dc5bd750">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a0151a88e0794af12a9e7932de2d7a928">PerlModGenerator::generatePerlModForPage</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="#ac5e00dabde23084cd671b0fe61772297">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="#a1f76d619b8096fc4446808b378b8ce14">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a4c2746ace65d9b91347502c11ccb43cf">processSection</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#aa01b0cef766ad1df71b59741da1d7d88">SectionManager::replace</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.</p>

</div>
</div>

### find() {#aa43fff2a2b489b77245b73478b391136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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




<p>Find an object given the key. Returns a pointer to the element if found or nullptr if it is not found.</p>


<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa43fff2a2b489b77245b73478b391136">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#aa43fff2a2b489b77245b73478b391136">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### find() {#aed32ef99019918a4c854c58e3fa4f918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const char * key)</td>
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




<p>Find an object given the key. Returns a pointer to the element if found or nullptr if it is not found.</p>


<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed32ef99019918a4c854c58e3fa4f918">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T *<a href="#aed32ef99019918a4c854c58e3fa4f918">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *key)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(std::string(key ? key : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a658afbac162b60faccc48da30fc39470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const char * key)</td>
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

<p>A non-const wrapper for find() const.</p>

<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a658afbac162b60faccc48da30fc39470">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a658afbac162b60faccc48da30fc39470">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a8049d249bddabf8b19862a1013c151da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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

<p>A non-const wrapper for find() const.</p>

<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8049d249bddabf8b19862a1013c151da">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a8049d249bddabf8b19862a1013c151da">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### find() {#a22821349a515cf453414cd64dc5bd750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find (const std::string &amp; key)</td>
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

<p>A non-const wrapper for find() const.</p>

<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22821349a515cf453414cd64dc5bd750">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T* <a href="#a22821349a515cf453414cd64dc5bd750">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight">T*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this).<a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>.</p>

</div>
</div>

### prepend() {#ac5e00dabde23084cd671b0fe61772297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend (const char * k, Args &amp;&amp;... args)</td>
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




<p>Prepends a new object to the ordered vector if it was not added already. Return a non-owning pointer to the newly added object, or to the existing object if it was already inserted before under the given key.</p>


<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5e00dabde23084cd671b0fe61772297">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T *<a href="#ac5e00dabde23084cd671b0fe61772297">prepend</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *k, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(k);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string key(k ? k : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> ptr = std::make_unique&lt;T&gt;(key.c_str(),std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_front(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a> and <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a>.</p>

</div>
</div>

### prepend() {#a1f76d619b8096fc4446808b378b8ce14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key, Args &amp;&amp;... args)</td>
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



<p>Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f76d619b8096fc4446808b378b8ce14">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    T *<a href="#a1f76d619b8096fc4446808b378b8ce14">prepend</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      T *result = <a href="#ad7659775b7de962b4fe0921456baf4f4">find</a>(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a73e8a4070e6a4399bde615098e2b074d">Ptr</a> ptr = std::make_unique&lt;T&gt;(key,std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        result = ptr.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>.emplace(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.push_front(std::move(ptr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>, <a href="#ab06db672a0fee1e5fe35340fb58f5a89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### rbegin() {#aca527abc73458116bb7c965a4417ab42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin ()</td>
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



<p>Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca527abc73458116bb7c965a4417ab42">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a> <a href="#aca527abc73458116bb7c965a4417ab42">rbegin</a>()               { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.rbegin();  }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rbegin() {#ac7bb388567d79b9d1e97198cdde6c3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin ()</td>
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



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7bb388567d79b9d1e97198cdde6c3f0">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a> <a href="#ac7bb388567d79b9d1e97198cdde6c3f0">rbegin</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.crbegin(); }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rend() {#a833c562ee3244c51c48acb2284e56f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rend ()</td>
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



<p>Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a833c562ee3244c51c48acb2284e56f89">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3f1e6d91dde39b1a948a67f401a5afaa">reverse_iterator</a> <a href="#a833c562ee3244c51c48acb2284e56f89">rend</a>()                 { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.rend();    }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### rend() {#aa92f5f3a31fd45d04e4bb38e04112f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rend ()</td>
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



<p>Definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa92f5f3a31fd45d04e4bb38e04112f5b">208</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#addcb5d41602952016038d8315e183d49">const_reverse_iterator</a> <a href="#aa92f5f3a31fd45d04e4bb38e04112f5b">rend</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.crend();   }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>

</div>
</div>

### size() {#ac1237f7ce32427ef9f9f334d0b97b1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::size ()</td>
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



<p>Definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1237f7ce32427ef9f9f334d0b97b1fb">210</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ac1237f7ce32427ef9f9f334d0b97b1fb">size</a>()</span><span class="doxyHighlightKeyword"> const                     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>.size();    }</span></span></div>

</div>


<p>Reference <a href="#a6c3a30d6871d3b560e6cd5360b164f46">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_entries {#a6c3a30d6871d3b560e6cd5360b164f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c3a30d6871d3b560e6cd5360b164f46">221</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac4cfcf6ff5a2f4c0cb16d52eded44146">Vec</a> <a href="#a6c3a30d6871d3b560e6cd5360b164f46">m_entries</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#addab86ba882be1f9c4137b6ceb095991">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a32a09a931c866f27807ceeabb48946f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#ab0ee1991e602ebd106de0fe5884979b6">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a4f9f85656f6481dc10277057d168d74e">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::begin</a>, <a href="#a97730addaf4399cae4511cea404a482b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::begin</a>, <a href="#a607048cb06f6ad98ae763d5734db73d4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::clear</a>, <a href="#a6150feb21a667df3826df38c1a0878fa">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="#a9a1da7be0df75c8ef81cdb3d825c6df3">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::empty</a>, <a href="#aa5583f9f11e470f5810a431a795f64d2">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::end</a>, <a href="#ae54a6938e3c17da11dd1d23a6217499d">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::end</a>, <a href="#adf2840eabd548e287a9db8c40d453eb2">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::operator[]</a>, <a href="#a58e9cb2ea5649b464cd9a34f58ace816">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::operator[]</a>, <a href="#ac5e00dabde23084cd671b0fe61772297">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="#a1f76d619b8096fc4446808b378b8ce14">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="#aca527abc73458116bb7c965a4417ab42">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin</a>, <a href="#ac7bb388567d79b9d1e97198cdde6c3f0">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rbegin</a>, <a href="#a833c562ee3244c51c48acb2284e56f89">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rend</a>, <a href="#aa92f5f3a31fd45d04e4bb38e04112f5b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::rend</a> and <a href="#ac1237f7ce32427ef9f9f334d0b97b1fb">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::size</a>.</p>

</div>
</div>

### m\_lookup {#ab06db672a0fee1e5fe35340fb58f5a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Hash = std::hash&lt;std::string&gt;, class KeyEqual = std::equal_to&lt;std::string&gt;, class Map = std::unordered_map&lt;std::string,T*,Hash,KeyEqual &gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Map LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::m_lookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab06db672a0fee1e5fe35340fb58f5a89">220</a></span><span class="doxyLineContent"><span class="doxyHighlight">    Map <a href="#ab06db672a0fee1e5fe35340fb58f5a89">m_lookup</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acddca8cb09f114936f6b80276f2c9c1b">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#addab86ba882be1f9c4137b6ceb095991">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a32a09a931c866f27807ceeabb48946f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#ab0ee1991e602ebd106de0fe5884979b6">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="#a607048cb06f6ad98ae763d5734db73d4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::clear</a>, <a href="#a6150feb21a667df3826df38c1a0878fa">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="#aa43fff2a2b489b77245b73478b391136">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#ac5e00dabde23084cd671b0fe61772297">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a> and <a href="#a1f76d619b8096fc4446808b378b8ce14">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
