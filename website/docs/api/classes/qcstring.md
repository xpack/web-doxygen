---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/qcstring
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `QCString` Class Reference

<p>This is an alternative implementation of <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class QCString { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/qcstring-h">src/qcstring.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SizeTag { <a href="#aac487a6223e056bcf37b9c7c0f993e30">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>creates a string with room for size characters <a href="#aac487a6223e056bcf37b9c7c0f993e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ecaca28abc410c18dc111da84a080c">QCString</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9d63203013767d7875ffe534899316">QCString</a> (std::string &amp;&amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd8dcd2de4abf36864f6f0c241f428a">QCString</a> (std::string_view sv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8641ee3cf5d71b73341533071e0603c5">QCString</a> (int)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e2da9d06bc6993d8a9daad3ff1699c">QCString</a> (const JavaCCString &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For converting a JavaCC string. <a href="#a22e2da9d06bc6993d8a9daad3ff1699c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc813fb23f557904aa94f100b37958d3">QCString</a> (size_t size, SizeTag t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2286f03edc20befca29cd2b2f57de1f6">QCString</a> (const char *str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>creates a string from a plain C string. <a href="#a2286f03edc20befca29cd2b2f57de1f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb844f296f351124bfe2e83b7c54976">QCString</a> (const char *str, size_t maxlen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>creates a string from <em>str</em> and copies over the first <em>maxlen</em> characters. <a href="#abeb844f296f351124bfe2e83b7c54976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a72c5f97b350b7d062bc2f823ebad82">operator=</a> (std::string_view sv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b2434c36272cc772fd0d3a09109652">operator=</a> (const JavaCCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8d791236dd93fd013f718a91bf6bbd">operator=</a> (const char *str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaces the contents by that of C string <em>str</em>. <a href="#afa8d791236dd93fd013f718a91bf6bbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52597e3bc7b763938231deb3a62a0dab">operator=</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39cc26ea20a11b2ef1bf77f1a8385606">operator+=</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d42ad9cb74319f635c13328cb3eca8">operator+=</a> (std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844a24565e79b45a3c0951e314408dc9">operator+=</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Appends string <em>str</em> to this string and returns a reference to the result. <a href="#a844a24565e79b45a3c0951e314408dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c280e74c6e56e739447a5908eeaeab">operator[]</a> (size_t i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indexing operator. <a href="#aa1c280e74c6e56e739447a5908eeaeab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565bc3e539ab20e33769c6ca429e180d">operator[]</a> (size_t i) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE iff the string is empty. <a href="#a621c4090d69ad7d05ef8e5234376c3d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16362990092a086b505e08f102df4dff">length</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the length of the string, not counting the 0-terminator. <a href="#a16362990092a086b505e08f102df4dff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a957be37e3b98707fc7e8daeff18e391b">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the length of the string, not counting the 0-terminator. <a href="#a957be37e3b98707fc7e8daeff18e391b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the contents of the string in the form of a 0-terminated C string. <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac853c00269498870dfefa8185f2ee79a">view</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a writable pointer to the data. <a href="#a5f5c9dc172d638c8d7b07010d100117a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747c587f5fee7b891e52909aa309323e">resize</a> (size_t newlen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4848e7058516bdbbcff3b43779aea30">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973167288278eae74d1d1c25313043fe">reserve</a> (size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve space for <em>size</em> bytes without changing the string contents. <a href="#a973167288278eae74d1d1c25313043fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08003d3e6c9acc46e4d392612ba492f7">fill</a> (char c, int len=-1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fills a string with a predefined character. <a href="#a08003d3e6c9acc46e4d392612ba492f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a> (const char *format,...)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0182ece6b76dad6475dafb53e2faaf10">find</a> (char c, int index=0, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5381d8547e101adef3ee87f8d54c9925">find</a> (const char *str, int index=0, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7227fa9c8db91de17b12305d5a6ca984">find</a> (const QCString &amp;str, int index=0, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47a6435c16d61d04fb448f1080b4e26">findRev</a> (char c, int index=-1, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6cbf7f8b8943606766d6e3d2e26fc70">findRev</a> (const char *str, int index=-1, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a> (char c, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2617e8fdb6c52fb762a52f7252d61ed">contains</a> (const char *str, bool cs=TRUE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a> (const QCString &amp;prefix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3524dfec9219699243b6baf0f33bd0f1">stripPrefix</a> (const char *prefix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf8b66312c4e97333219cc344c11a4f">left</a> (size_t len) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4aa5417f6a834f28c7148a1fe262d5">right</a> (size_t len) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27136caf9c0bc4daca574cda6f113551">mid</a> (size_t index, size_t len=static_cast&lt; size_t &gt;(-1)) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33688239622e659cfb469fbd62c9cccb">lower</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns a copy of this string with leading and trailing whitespace removed <a href="#a66269a694d9e6961bfd145bb4ca72f42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6444196e54d0b736cef5c9edd8c262d9">stripLeadingAndTrailingEmptyLines</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af428b9307683dc2c090f7d837138b438">quoted</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5612f003ab58972eb5769811876c5e3">removeWhiteSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns a copy of this string with all whitespace removed <a href="#ae5612f003ab58972eb5769811876c5e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>return a copy of this string with leading and trailing whitespace removed and multiple whitespace characters replaced by a single space <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a> (unsigned int n) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> (size_t index, const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc8c31db7525ff4aab929f6526675689">insert</a> (size_t index, std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0acc09ca029c0a255063a7dc610be340">insert</a> (size_t index, const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecd047709be2b8eda218b76bf9c385b">insert</a> (size_t index, char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a> (char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303cf8f6a8f57a92e3bda9423ca643aa">append</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fdaff21dfb70be75af14aed604e721b">append</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747c5c5f38d0e2e43ac2716fd7413247">append</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc397b8b45d77dbdb45a921ee40ff68">append</a> (std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffefc809c8b24e32df929c2985bdf48">prepend</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792b11db11f131e280229450e9ad4fba">prepend</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8270e394feda059b463a3588a41d6e5e">prepend</a> (std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a> (size_t index, size_t len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab536413a2bab9fe536e82067a3f164ed">replace</a> (size_t index, size_t len, const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfb73b0f862461d60da84504fa4d4cd">toShort</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d31136b4f5f614640bd277d49182135">toUShort</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43def7ec8f0cdca5bf722f952e0cf19">toUInt</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524e1cd9e1c24e91d57b1cb91513fa67">toUInt64</a> (bool *ok=nullptr, int base=10) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a> (short n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b813d24e05da8782921d21abda996f">setNum</a> (uint16_t n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a985317d53986ff869f6200eba01da503">setNum</a> (int n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ba2a3c200768b4f3b062ea80c90a20">setNum</a> (uint32_t n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258a420449cd4af46dca39fc4d5966ee">setNum</a> (long n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f922d046d633efe346301f9f4a2e1d">setNum</a> (long long n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91737ecae84142dc8f0b224e6e3ab6b4">setNum</a> (unsigned long long n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce207a13873ddad6ceba4e7ed475736">setNum</a> (unsigned long n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a> (const char *s) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd585269e99db0640d91e8179152bb34">startsWith</a> (const std::string &amp;s) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a> (const QCString &amp;s) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a> (const char *s) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e46356724349472724ef65339235f21">endsWith</a> (const std::string &amp;s) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a> (const QCString &amp;s) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875e9ad762554ef12f3ed69b015bb245">str</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a> (size_t i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the character at index <em>i</em>. <a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb462b152dd61c53ccde9b7194c167a8">at</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a></td>
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

<p>This is an alternative implementation of <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>.</p>


<p>It provides basically the same functions but uses std::string as the underlying string type</p>

<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### SizeTag {#aac487a6223e056bcf37b9c7c0f993e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum QCString::SizeTag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>creates a string with room for size characters</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitSize<a id="aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] size</td>
<td class="doxyParamItemDescription"><p>the number of character to allocate (also counting the 0-terminator!)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#aac487a6223e056bcf37b9c7c0f993e30">SizeTag</a> { <a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">ExplicitSize</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### QCString() {#ad691e1087cc03e14e00d1147ae0ecab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

Referenced by <a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a>, <a href="#a303cf8f6a8f57a92e3bda9423ca643aa">append</a>, <a href="#a4fdaff21dfb70be75af14aed604e721b">append</a>, <a href="#a747c5c5f38d0e2e43ac2716fd7413247">append</a>, <a href="#a6bc397b8b45d77dbdb45a921ee40ff68">append</a>, <a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a>, <a href="#a7227fa9c8db91de17b12305d5a6ca984">find</a>, <a href="#abecd047709be2b8eda218b76bf9c385b">insert</a>, <a href="#a0acc09ca029c0a255063a7dc610be340">insert</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="#afc8c31db7525ff4aab929f6526675689">insert</a>, <a href="#aecf8b66312c4e97333219cc344c11a4f">left</a>, <a href="#a33688239622e659cfb469fbd62c9cccb">lower</a>, <a href="#a27136caf9c0bc4daca574cda6f113551">mid</a>, <a href="#a844a24565e79b45a3c0951e314408dc9">operator+=</a>, <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>, <a href="#a39cc26ea20a11b2ef1bf77f1a8385606">operator+=</a>, <a href="#a62d42ad9cb74319f635c13328cb3eca8">operator+=</a>, <a href="#afa8d791236dd93fd013f718a91bf6bbd">operator=</a>, <a href="#a28b2434c36272cc772fd0d3a09109652">operator=</a>, <a href="#a52597e3bc7b763938231deb3a62a0dab">operator=</a>, <a href="#a1a72c5f97b350b7d062bc2f823ebad82">operator=</a>, <a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>, <a href="#acffefc809c8b24e32df929c2985bdf48">prepend</a>, <a href="#a792b11db11f131e280229450e9ad4fba">prepend</a>, <a href="#a8270e394feda059b463a3588a41d6e5e">prepend</a>, <a href="#af428b9307683dc2c090f7d837138b438">quoted</a>, <a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>, <a href="#ae5612f003ab58972eb5769811876c5e3">removeWhiteSpace</a>, <a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a>, <a href="#ab536413a2bab9fe536e82067a3f164ed">replace</a>, <a href="#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>, <a href="#a985317d53986ff869f6200eba01da503">setNum</a>, <a href="#a96f922d046d633efe346301f9f4a2e1d">setNum</a>, <a href="#a258a420449cd4af46dca39fc4d5966ee">setNum</a>, <a href="#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>, <a href="#a26b813d24e05da8782921d21abda996f">setNum</a>, <a href="#a12ba2a3c200768b4f3b062ea80c90a20">setNum</a>, <a href="#a91737ecae84142dc8f0b224e6e3ab6b4">setNum</a>, <a href="#a9ce207a13873ddad6ceba4e7ed475736">setNum</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>, <a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a>, <a href="#a6444196e54d0b736cef5c9edd8c262d9">stripLeadingAndTrailingEmptyLines</a>, <a href="#a3524dfec9219699243b6baf0f33bd0f1">stripPrefix</a>, <a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>, <a href="#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a> and <a href="#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a>.
</div>
</div>

### QCString() {#af7ecaca28abc410c18dc111da84a080c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (const std::string &amp; s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7ecaca28abc410c18dc111da84a080c">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#af7ecaca28abc410c18dc111da84a080c">QCString</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s ) : <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>(s) {}</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### QCString() {#a6e9d63203013767d7875ffe534899316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (std::string &amp;&amp; s)</td>
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


<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e9d63203013767d7875ffe534899316">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6e9d63203013767d7875ffe534899316">QCString</a>( std::string &amp;&amp;s) : <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>(std::move(s)) {}</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### QCString() {#a0cd8dcd2de4abf36864f6f0c241f428a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (std::string_view sv)</td>
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


<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cd8dcd2de4abf36864f6f0c241f428a">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0cd8dcd2de4abf36864f6f0c241f428a">QCString</a>( std::string_view sv) : <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>(sv) {}</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### QCString() {#a8641ee3cf5d71b73341533071e0603c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>
</div>
</div>

### QCString() {#a22e2da9d06bc6993d8a9daad3ff1699c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (const <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> &amp; s)</td>
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
<p>For converting a JavaCC string.</p>

<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22e2da9d06bc6993d8a9daad3ff1699c">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a22e2da9d06bc6993d8a9daad3ff1699c">QCString</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(s.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.data(),s.data(),s.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### QCString() {#acc813fb23f557904aa94f100b37958d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (size_t size, <a href="#aac487a6223e056bcf37b9c7c0f993e30">SizeTag</a> t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc813fb23f557904aa94f100b37958d3">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#acc813fb23f557904aa94f100b37958d3">QCString</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>, <a href="#aac487a6223e056bcf37b9c7c0f993e30">SizeTag</a> t) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(<a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>); }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>.
</div>
</div>

### QCString() {#a2286f03edc20befca29cd2b2f57de1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (const char * str)</td>
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
<p>creates a string from a plain C string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] str</td>
<td class="doxyParamItemDescription"><p>A zero terminated C string. When 0 an empty string is created.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2286f03edc20befca29cd2b2f57de1f6">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2286f03edc20befca29cd2b2f57de1f6">QCString</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a> ) : <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>?<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>:</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">) {}</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### QCString() {#abeb844f296f351124bfe2e83b7c54976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString::QCString (const char * str, size_t maxlen)</td>
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
<p>creates a string from <em>str</em> and copies over the first <em>maxlen</em> characters.</p>

<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abeb844f296f351124bfe2e83b7c54976">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abeb844f296f351124bfe2e83b7c54976">QCString</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> maxlen ) : <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>?<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>:</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(maxlen); }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&#91;&#93;() {#aa1c280e74c6e56e739447a5908eeaeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char &amp; QCString::operator[] (size_t i)</td>
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
<p>Indexing operator.</p>


<p>Equivalent to <a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">at()</a>.</p>

<p>Definition at line 589 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1c280e74c6e56e739447a5908eeaeab">589</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#aa1c280e74c6e56e739447a5908eeaeab">operator[]</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### operator&#91;&#93;() {#a565bc3e539ab20e33769c6ca429e180d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char &amp; QCString::operator[] (size_t i)</td>
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


<p>Definition at line 594 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a565bc3e539ab20e33769c6ca429e180d">594</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#a565bc3e539ab20e33769c6ca429e180d">operator[]</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### operator+=() {#a3f8a3c4ff3e86b352ac49ee366dc2c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator+= (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 542 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">542</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>+=s.<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.

Referenced by <a href="#a303cf8f6a8f57a92e3bda9423ca643aa">append</a>, <a href="#a4fdaff21dfb70be75af14aed604e721b">append</a>, <a href="#a747c5c5f38d0e2e43ac2716fd7413247">append</a> and <a href="#a6bc397b8b45d77dbdb45a921ee40ff68">append</a>.
</div>
</div>

### operator+=() {#a39cc26ea20a11b2ef1bf77f1a8385606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator+= (const std::string &amp; s)</td>
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


<p>Definition at line 548 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39cc26ea20a11b2ef1bf77f1a8385606">548</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a39cc26ea20a11b2ef1bf77f1a8385606">operator+=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### operator+=() {#a62d42ad9cb74319f635c13328cb3eca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator+= (std::string_view s)</td>
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


<p>Definition at line 554 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62d42ad9cb74319f635c13328cb3eca8">554</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a62d42ad9cb74319f635c13328cb3eca8">operator+=</a>(std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### operator+=() {#a844a24565e79b45a3c0951e314408dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator+= (const char * s)</td>
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
<p>Appends string <em>str</em> to this string and returns a reference to the result.</p>

<p>Definition at line 561 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a844a24565e79b45a3c0951e314408dc9">561</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a844a24565e79b45a3c0951e314408dc9">operator+=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s) <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### operator=() {#a1a72c5f97b350b7d062bc2f823ebad82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator= (std::string_view sv)</td>
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


<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a72c5f97b350b7d062bc2f823ebad82">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a1a72c5f97b350b7d062bc2f823ebad82">operator=</a>(std::string_view sv) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>=sv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### operator=() {#a28b2434c36272cc772fd0d3a09109652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator= (const <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> &amp; s)</td>
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


<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28b2434c36272cc772fd0d3a09109652">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a28b2434c36272cc772fd0d3a09109652">operator=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(s.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.data(),s.data(),s.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### operator=() {#afa8d791236dd93fd013f718a91bf6bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator= (const char * str)</td>
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
<p>replaces the contents by that of C string <em>str</em>.</p>

<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa8d791236dd93fd013f718a91bf6bbd">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#afa8d791236dd93fd013f718a91bf6bbd">operator=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>?<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>:</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### operator=() {#a52597e3bc7b763938231deb3a62a0dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::operator= (const std::string &amp; s)</td>
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


<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52597e3bc7b763938231deb3a62a0dab">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a52597e3bc7b763938231deb3a62a0dab">operator=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = s; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### append() {#a8f0a381fdae1427b1182baf0abde21e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::append (char c)</td>
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


<p>Definition at line 381 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f0a381fdae1427b1182baf0abde21e7">381</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ab657e2797fb2f8d57ca202215fc2003d">FlowChart::alignCommentNode</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a38b6783aaabbed92ec114e917385f739">appStringLower</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a30e9e6fd4264e1d7dd92eb516c9feb6e">MemberDefImpl::getDeclType</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6524e8718f3f956610df4dfc71be204c">VhdlDocGen::getProcessNumber</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a1f81275d1115ffda9759c5bd96fa9986">operator+</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a0f5d7b1a37d084b7229b8fcc0dd0151d">operator+</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="#af428b9307683dc2c090f7d837138b438">quoted</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a065cc165c287399167d790bd59ac60e0">MemberDefImpl::sourceRefName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>.
</div>
</div>

### append() {#a303cf8f6a8f57a92e3bda9423ca643aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::append (const char * s)</td>
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


<p>Definition at line 387 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a303cf8f6a8f57a92e3bda9423ca643aa">387</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a303cf8f6a8f57a92e3bda9423ca643aa">append</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### append() {#a4fdaff21dfb70be75af14aed604e721b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::append (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 392 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fdaff21dfb70be75af14aed604e721b">392</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a4fdaff21dfb70be75af14aed604e721b">append</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### append() {#a747c5c5f38d0e2e43ac2716fd7413247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::append (const std::string &amp; s)</td>
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


<p>Definition at line 397 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a747c5c5f38d0e2e43ac2716fd7413247">397</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a747c5c5f38d0e2e43ac2716fd7413247">append</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### append() {#a6bc397b8b45d77dbdb45a921ee40ff68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::append (std::string_view s)</td>
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


<p>Definition at line 402 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bc397b8b45d77dbdb45a921ee40ff68">402</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a6bc397b8b45d77dbdb45a921ee40ff68">append</a>( std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### at() {#a4c8be5d062cc14919b53ff0a3c8f9a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char &amp; QCString::at (size_t i)</td>
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
<p>Returns a reference to the character at index <em>i</em>.</p>

<p>Definition at line 578 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">578</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::&#95;setBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/classes/qhp/#ad187b30da8187b859054c6271108b660">Qhp::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#ab09e45c115a5beefe878b915613bd3a3">checkVhdlString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acf309728fac71ec225044c1afe6ae9f7">computeVerifiedDotPath</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a7df6021b8c7a5e9d81c3e586bea19a25">TranslatorPersian::convertDigitsToFarsi</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a08d427ab614e1a8142b07a629730673f">extractPartAfterNewLine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a019e4dfdc4fe1a34460b8f7bb8dfe0fa">findEndOfTemplate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acfc81350dc516af20831bcb14d6788c2">getCanonicalTemplateSpec</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad3269d7d65675a5e83889f4a98f5610b">getExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a9b5774d3b3547b5143e86594853498">getNextId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afd249e264b966d05a54b740e3d43ad6e">getScopeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aae351e4e8775385568dd3d77f52707e8">NamespaceDefImpl::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a373928f3b61089f84cb4ee946474792f">leftScopeMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/sitemap-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#acca4ea7f41c631ad64fc467e7bb24615">nameIsOperator</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a4e52d619e02e6a48b41aa65affcac398">node2URL</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a315f64205ff8e9d75ddd63e31f068269">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53f751007ffe5b7c105c3821039a970c">processString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae0c5a702c29f403e331441abfe289d5b">rightScopeMatch</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a544c6fd0814756e0e4ab69eac035ff7f">startsWithKeyword</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a085c52ce4351470497b03309e77228cc">stringize</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78d33655f54cd45e22070b58a6dce6b6">stripScope</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a255ee5917ab88a261843376db88293a5">stripTemplateSpecifiers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae81df9187a70102c6f47ca6c2c5012f4">stripTrailingWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a84a2aa61638b8af08560219e2a5140f1">ConfigOption::writeStringList</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>.
</div>
</div>

### at() {#acb462b152dd61c53ccde9b7194c167a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char &amp; QCString::at (size_t i)</td>
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


<p>Definition at line 583 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb462b152dd61c53ccde9b7194c167a8">583</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#acb462b152dd61c53ccde9b7194c167a8">at</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### clear() {#af4848e7058516bdbbcff3b43779aea30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QCString::clear ()</td>
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


<p>Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af4848e7058516bdbbcff3b43779aea30">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af4848e7058516bdbbcff3b43779aea30">clear</a>() { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.clear(); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docgroup/#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a38b6783aaabbed92ec114e917385f739">appStringLower</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aaf9011f7d4c2a48af197236c52d0a95d">codifyMapLines</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a319a5456c54411f74e047b8dad2de802">expandMacro</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a7656679a311cb6f8c5269ada7d1f8bd4">fixArgumentListForJavaScript</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a60f7798b2a14de4350512176374a2228">initMethodProtection</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2ee9959a879f505d8e3296acd74f4758">ClassDefImpl::writeMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a>.
</div>
</div>

### contains() {#aeeedb2810a85c682c2f2a86bcd2355a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::contains (char c, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 195 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeeedb2810a85c682c2f2a86bcd2355a7">143</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a16362990092a086b505e08f102df4dff">length</a>()==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*pos) </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*pos++ == c) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    c = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*pos)==c) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4584e2262b81979f6d9b88c070c78753">VhdlDocGen::parseForConfig</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>.
</div>
</div>

### contains() {#ab2617e8fdb6c52fb762a52f7252d61ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::contains (const char * str, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 196 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2617e8fdb6c52fb762a52f7252d61ed">164</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || <a href="#a16362990092a086b505e08f102df4dff">length</a>()==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(pos,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>,len)==0) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(pos,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>,len)==0) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### data() {#ac3aa3ac1a1c36d3305eba22a2eb0d098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * QCString::data ()</td>
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
<p>Returns a pointer to the contents of the string in the form of a 0-terminated C string.</p>

<p>Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.c_str(); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::&#95;docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#a320fc1c937898dd004caadd235e6d68a">SectionManager::add</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#a1dd9ba2dc2586e4dcd08ea7da6d93b69">Crawlmap::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#af6acf966d7ed7500f4ab36fbdce70db0">buildFileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aefbbb766c678a158e56f49d59a20d8cd">checkMarkdownMainfile</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a45411d390f8310e821828edefffa0759">FlowChart::codify</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ace27d46d07e19112fc6ee3411915c8ea">LatexCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#a370900ffa665f2d187c9d87571de2fdf">ManCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acaccd6e77d3f7f597669a7c541b623a1">RTFCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/lexcode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5a47760391ae7b0e270bd1de323be1e0">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aaf9011f7d4c2a48af197236c52d0a95d">codifyMapLines</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#a9e1db762aaf71f44e596c234a11248c0">FilterCache::compileLineOffsets</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>, <a href="#ab2617e8fdb6c52fb762a52f7252d61ed">contains</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a6078df856ea98140e2210721d1175764">convertIndexWordToAnchor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7d7c9238115c2656c20621678519cb87">convertToJSString</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08216fc437af3c55e1b7ac51430744f9">Portable::correctPath</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#af50f1fc37531bed71dba97fcf1ea5dd9">do&#95;mscgen&#95;generate</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af41254fa358458e4e1a018477f5107da">ManGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a894bfecdbda01b83760c93a6a6947b9d">HtmlGenerator::docify&#95;</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8d91af0a6807cf2a6b66896bfdef6732">encodeDirName</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad860c94401483cee6345e6dd71bab597">escapeAt</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#ac7978878c5e2989e9739423aa06f805a">extractBoundingBox</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#acd4ff9a433984cc6fb8e9b6f47284420">HtmlDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a72964fa569229687454f00fe4dc4ab45">ManDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a02ac65b43b4122de86989aed6d356df1">RTFDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a41b5f683e302b49a51ffc8f4199e6d38">TextDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="#a0182ece6b76dad6475dafb53e2faaf10">find</a>, <a href="#a5381d8547e101adef3ee87f8d54c9925">find</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>, <a href="#ab6cbf7f8b8943606766d6e3d2e26fc70">findRev</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a640bce791d53e83dcbd47f7ab01620e8">DocTokenizer::findSections</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a34f3686f7bccb7f7d9ef304724198661">VhdlDocGen::findVhdlClass</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2086de9221c9c0a17efc40915a054852">generateAnonymousAnchor</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#ac5f1e3b27673fb0ab040a07469c29a87">ParserManager::getParsers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae052d7dcea3289dd204d8d425cf9d4c9">getPrefixIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aba6653be2d238e1fc793706547950107">getProjectId</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#ad81bb3ba85d992b1571d9f4b54068fb2">PerlModOutput::iaddQuoted</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#aaf8015f456496f1510c8e8643f959376">HtmlHelpRecoder::initialize</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e975b2170ce769882c4bbb8f2cb8b94">isLowerCase</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a37bf597b522fe84aefa564de5b8489c2">latexEscapePDFString</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac0fd4772eabf2904003c3e2608882c80">letterToLabel</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aa00031a2d8766a111e037878b9b2f3ca">VHDLOutlineParser::lineCount</a>, <a href="/web-doxygen/docs/api/files/src/defargs-l/#aac9470d1061fbdc10e05184c45712c29">nameIsActuallyPartOfType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a51ba7ef8a69ba1d6ced3d30136697f00">operator!=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a827bfa735bd7a4e0d7cb16c81d1c42f1">operator!=</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab3dc4aca49387c2801b733951162e52c">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a960b5f05edbdfd2ab749e6f1358fdfa0">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ac8faec71974f8983332aa0e11a946276">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a96d361413f4d2fd8850d999e060ff870">operator&lt;</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ad88e4295035e7cf362d7f55b06f73ba6">operator&lt;</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07a42b0818f0d832aebe8df9195580fa">operator&lt;=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aaf859be3755b7aff5639142161bc7606">operator&lt;=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a632cd3a80fcab139f461a41f3cc60e8d">operator==</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ad63779242f7ec7f1f63973d13a545b85">operator==</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aebf87e7db11cc3a6034475a7bbf4a63d">operator&gt;</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a21042d2bb0fb0aefd0afef200ff68648">operator&gt;</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a5c05a9f1060373e7b8cdcd50da7502de">operator&gt;=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a37897e7d8cd6ae9139071d10556b80a2">operator&gt;=</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/lexcodeparser/#a907e618c99ef07aa00fc0604062e3929">LexCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/sqlcodeparser/#ad4cfac05d7a0c2354cdb90992b1e0248">SQLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/xmlcodeparser/#a1e7283cd50a9220c8381cbdf953702ca">XMLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>, <a href="/web-doxygen/docs/api/structs/vhdloutlineparser/private/#a09e1a5b366fadb1761f46049e67df6c5">VHDLOutlineParser::Private::parseVhdlfile</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a15b92ac03be9e8f4d95d5e881342d83c">Portable::popen</a>, <a href="#acffefc809c8b24e32df929c2985bdf48">prepend</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a1cbb9db483a1cd53acc3671d25399cda">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#adbc3f136c91cf966d67fa45dc66d7872">qstrcmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a2d1063a4c1d2c36a05f8e79bf5265de0">qstrcmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a06565348139db73f6fe50d33d3fb4c2d">qstrcmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a33f4db19d3805a1cf2de3560155442fd">qstricmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a97be1dda81236d5b70232705817f55f5">qstricmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a74c210fdf334f6a6aacec23bae6afda8">qstricmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a56fea00f875a74ba5c3fff176ca908d9">qstricmp&#95;sort</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a32ac0dd364b2ad4233c2e64dedb40e97">qstricmp&#95;sort</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#af84700f1e6f0e39b5fe2e2f0653a943a">qstricmp&#95;sort</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#acc7c52aee841813f28c7e9227b5bea57">qstrnicmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a87c125e95623108226932004a5e061d1">qstrnicmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a232d1f8a5b76f765dec1cf7ce2ad1cd0">qstrnicmp</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3f2329035cfde039380d267efff68c76">removeEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#aa01b0cef766ad1df71b59741da1d7d88">SectionManager::replace</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a5f5bce72519f9278f849a2c4cf936393">CitationManager::replaceFormulas</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/classes/coloredimage/#ae4a3366368b665b83c8b821fd9bdeae7">ColoredImage::save</a>, <a href="/web-doxygen/docs/api/classes/image/#aa60b6e62896aa1fbd62d7df3f02aaf7e">Image::save</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a931044da5493c1d83ca77898996140c4">MemberDefImpl::setAnchor</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/private/#af8a551d5ba6e33523a40c372ec854203">DefinitionImpl::Private::setDefFileName</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#abd244447df22d110ad410b69c357fdf3">Portable::setenv</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a45928a3aa04b29c259685a5d3f6cbf4d">skipToEndMarker</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>, <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae81df9187a70102c6f47ca6c2c5012f4">stripTrailingWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>, <a href="#a524e1cd9e1c24e91d57b1cb91513fa67">toUInt64</a>, <a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a75237d30f908ef839f400a0fe7584f9a">unescapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a2769e7f4b078110dae0ca454481d5e41">unescapeCRef</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a394e935b6fd1899b26f8987f89a4cbfb">Portable::unlink</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ab8df06c9b8d04453c03cd380baa8e0b8">DocTokenizer::unputString</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ac2e29048cffc72c3bed439cff5b02cd4">Portable::unsetenv</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#add59fcdb30edd4ebfd1b0da8787e2e52">ManCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aefd632b8f888c312d4d67dffa15f5669">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af173fc80e34a6372764c46d3cf4c7758">HtmlDocVisitor::writeObfuscatedMailAddress</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a53279dc86a635990c995e61bc3b7104c">DocbookGenerator::writePageLink</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/image/#a9548b8956604519c4260cbdaf7854792">Image::writeString</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a>.
</div>
</div>

### endsWith() {#a419394d9b5a9a18d4465ce4017f646d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::endsWith (const char * s)</td>
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


<p>Definition at line 509 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a419394d9b5a9a18d4465ce4017f646d0">509</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty() || s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = strlen(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()&gt;=l &amp;&amp; <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.compare(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()-l, l, s, l)==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a717f9e550bc2df9508126b7cb4dd23c3">demangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/cite-cpp/#a883e572433098a2f3714d29ddc109fc8">getBibFile</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2dd347b6be51aa404a4e6bc679736606">MemberDefImpl::init</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">DiagramItem::label</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa39c36a133f69ff84e4d617e3915f9c8">startOfRequiresExpression</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a31cfb988a49ee5b4f6e0f64dded34507">MemberDefImpl::warnIfUndocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a0c852a5df0dd82d83c4ec8b99f4e3937">DocSets::writeToken</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>.
</div>
</div>

### endsWith() {#a6e46356724349472724ef65339235f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::endsWith (const std::string &amp; s)</td>
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


<p>Definition at line 516 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e46356724349472724ef65339235f21">516</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6e46356724349472724ef65339235f21">endsWith</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()&gt;=l &amp;&amp; <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.compare(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()-l, l, s)==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### endsWith() {#a320d19fe1ec83dedf40139c185c02157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::endsWith (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 522 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a320d19fe1ec83dedf40139c185c02157">522</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = s.<a href="#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()&gt;=l &amp;&amp; <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.compare(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.length()-l, l, s.<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>())==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### fill() {#a08003d3e6c9acc46e4d392612ba492f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QCString::fill (char c, int len=-1)</td>
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
<p>Fills a string with a predefined character.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] c</td>
<td class="doxyParamItemDescription"><p>the character used to fill the string with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] len</td>
<td class="doxyParamItemDescription"><p>the number of character to fill. Use -1 to fill the whole string.</p></td>
</tr>
</table>
</dd>
</dl>

:::info
<p>the string will be resized to contain <em>len</em> characters. The contents of the string will be lost.</p>
:::


<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a08003d3e6c9acc46e4d392612ba492f7">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a08003d3e6c9acc46e4d392612ba492f7">fill</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = -1 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = len==-1 ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size()) : len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::string(l,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#ab657e2797fb2f8d57ca202215fc2003d">FlowChart::alignCommentNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aaf9011f7d4c2a48af197236c52d0a95d">codifyMapLines</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a2945edc16c199a62e84ee85d81b9c854">generateJSTree</a>, <a href="/web-doxygen/docs/api/structs/docsets/private/#a826ea3c2606c786218f2107046b8b018">DocSets::Private::indent</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a4c5beb634b87459054e96cfa6e07717a">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a4ce763b29a44b5b477602993c33842b9">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aad6d88a7940699bbb17fa4648d6007a9">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aad902c41e3df81277b2bf6f1e95f466d">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a001e5e4b6b99ed83d3333cc3adf5afd2">printNavTree</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ade547304a708b89e5a5f55f7fb9db151">writeTemplateArgumentList</a>.
</div>
</div>

### find() {#a0182ece6b76dad6475dafb53e2faaf10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::find (char c, int index=0, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 188 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0182ece6b76dad6475dafb53e2faaf10">43</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0 || index&gt;=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>())) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1; </span><span class="doxyHighlightComment">// index outside string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    pos = strchr(<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+index,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    pos = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    c = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*pos &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*pos)!=c) pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!*pos &amp;&amp; c) pos=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// not found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pos ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(pos - <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a662691ab2b83958aaa9bdddb1a974c6f">MemberDefImpl::&#95;computeIsConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad948fb0ac4fb22597763862c59930372">MemberDefImpl::&#95;computeIsDestructor</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::&#95;docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::&#95;writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::&#95;writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac808ed1ddf94dd08b95d1ee433e96359">buildDictionaryList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6c44f1592724165dbf7e5a36be496b5d">buildSequenceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a685b08b025bb0139299eb40a0704df31">buildVarList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad28f49b99078162fd63bd325db5c2b2b">VhdlDocGen::convertFileNameToClassName</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a20350e5803a50856a69419c6473dd5a1">MemberList::countEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a717f9e550bc2df9508126b7cb4dd23c3">demangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#aa0944a06a26c8f552be061cd5060baa1">DocInternalRef::DocInternalRef</a>, <a href="/web-doxygen/docs/api/files/src/portable-cpp/#a1a05b42d6baa2f85ed112c8a7c67ac01">ExistsOnPath</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3a1173b85597fdb88c5bf3f6d7f9e024">extractBeginRawStringDelimiter</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#ac7978878c5e2989e9739423aa06f805a">extractBoundingBox</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91b99c5ed2e4b31b81c9eda9514c53da">extractClassName</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa92d2aaaadff51d927a9629cdad82a9">extractNoExcept</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a08d427ab614e1a8142b07a629730673f">extractPartAfterNewLine</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="#a7227fa9c8db91de17b12305d5a6ca984">find</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aa2b4c58062de6e3075936abc6c29dd7e">getTemplateArgumentsFromName</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a01336ef49f88d4dd7f574c3db13ad774">isCastKeyword</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9905c57ded9f8f4db3bbe658e510f781">MemberDefImpl::isDocumentedFriendClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa41ca3cde0467d35291f6d6a48be0c44">ClassDefImpl::isExtension</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae6d03857fff127078a6b0a74f36e05bb">MemberDefImpl::isFunctionPtr</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0947f1f8c60660017b41863e47fc61be">isRecursiveBaseClass</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae604f9461d7685908488ead7a6d72ca0">DocImage::isSVG</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a29dc16dcef3e9ca42657dcf3bfd8d53a">lineBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a52cc252e59332d38e224e11bd019f632">matchCanonicalTypes</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#abc751e8cc79b9f7cc8040ba7ecce6e1f">DirDefImpl::mergeDirectoryInTree</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#acca4ea7f41c631ad64fc467e7bb24615">nameIsOperator</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a7910d0ac9f615f9ce451bd0c71d15da6">VHDLOutlineParser::oneLineComment</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abafe8d30316505f2a4c60ec608437ebc">projectLogoFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a5f5bce72519f9278f849a2c4cf936393">CitationManager::replaceFormulas</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#ad8c27cb35135c54eaccd3482cc97c067">setJavaProtection</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a67e22ceaa05ae493f2f3892681aec351">splitString</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5b4fd5c937a0d1bb806033635f35cc99">stripDeclKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a848aaabaf4d7b73351e6850d05254d99">stripKeyword</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a15f807d04ca6a15d183d7c05396bae30">trimBaseClassScope</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ac2e29048cffc72c3bed439cff5b02cd4">Portable::unsetenv</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1d51f3aad1177695f1c4a6c1340bfa0b">MemberDefImpl::warnIfUndocumented</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a31cfb988a49ee5b4f6e0f64dded34507">MemberDefImpl::warnIfUndocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a0332e2befe926de95b367c391a0ac70c">DotNode::writeDEF</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a4be56bbbeefd5d44b58d28f05c446725">DotNode::writeDocbook</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a92275d99afc832afc51d7e0deec3afe6">LatexDocVisitor::writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#aed2051e58bce93b9250b99108a77ae00">DotNode::writeXML</a>.
</div>
</div>

### find() {#a5381d8547e101adef3ee87f8d54c9925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::find (const char * str, int index=0, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 189 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5381d8547e101adef3ee87f8d54c9925">61</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0 || index&gt;=l) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1; </span><span class="doxyHighlightComment">// index outside string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>)  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;               </span><span class="doxyHighlightComment">// no string to search for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!*<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index;           </span><span class="doxyHighlightComment">// empty string matching at index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs) </span><span class="doxyHighlightComment">// case sensitive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    pos = strstr(<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+index,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// case insensitive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    pos = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(pos,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>,len)==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!*pos) pos = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// not found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pos ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(pos - <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### find() {#a7227fa9c8db91de17b12305d5a6ca984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, int index=0, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 190 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7227fa9c8db91de17b12305d5a6ca984">86</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0182ece6b76dad6475dafb53e2faaf10">find</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.data(),index,cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a0182ece6b76dad6475dafb53e2faaf10">find</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### findRev() {#ab47a6435c16d61d04fb448f1080b4e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::findRev (char c, int index=-1, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 192 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab47a6435c16d61d04fb448f1080b4e26">91</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *b = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1; </span><span class="doxyHighlightComment">// empty string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0) </span><span class="doxyHighlightComment">// start from end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      pos = strrchr(b,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pos ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(pos - b) : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    index=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;len) </span><span class="doxyHighlightComment">// bad index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  pos = b+index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( pos&gt;=b &amp;&amp; *pos!=c) pos--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    c = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( pos&gt;=b &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*pos)!=c) pos--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pos&gt;=b ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(pos - b) : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a83c5141d20cfce3f391f36e0d9ace3d6">TooltipManager::addTooltip</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aefb94fa4d5f207d7a1aa6c7fb5ab54b5">convertFileId2Var</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a20350e5803a50856a69419c6473dd5a1">MemberList::countEnumValues</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad2143a92408c0b36271fbf7dbe84f4f7">findParameterList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a5cba77d157c52ffaef77df9fb2782230">getBaseNameOfOutput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad7fe83480a1c139afa09ab1183da5ca5">getParserForFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a02c9248de7bb1fd9c72a3dc3b537cd0e">FileDefImpl::isDocumentationFile</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aae351e4e8775385568dd3d77f52707e8">NamespaceDefImpl::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ad4ef2fd3be12660847c709847af5d620">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ad4ef2fd3be12660847c709847af5d620">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a411f4f042964d6e24c0376f1378da1a8">VhdlDocGen::parseForBinding</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4584e2262b81979f6d9b88c070c78753">VhdlDocGen::parseForConfig</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aa32a03da6438377d962da12f57b0f2c0">VHDLOutlineParser::popLabel</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5935e8ddff8337f8a43689e2713c8067">ManGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a87e8230599f42efce2bbca2f35e31521">NamespaceDefImpl::updateLocalName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#a1cb314bd0d605efa7019319e3da26870">DotNode::writeUrl</a>.
</div>
</div>

### findRev() {#ab6cbf7f8b8943606766d6e3d2e26fc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::findRev (const char * str, int index=-1, bool cs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 193 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6cbf7f8b8943606766d6e3d2e26fc70">123</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> cs)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> slen = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0) index = len-slen; </span><span class="doxyHighlightComment">// start from end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;len) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1; </span><span class="doxyHighlightComment">// bad index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index+slen&gt;len) index=len-slen; </span><span class="doxyHighlightComment">// str would be too long</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1; </span><span class="doxyHighlightComment">// no match possible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pos = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs) </span><span class="doxyHighlightComment">// case sensitive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=index; i&gt;=0; i--) </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(pos--,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>,slen)==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// case insensitive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=index; i&gt;=0; i--) </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(pos,<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>,slen)==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### insert() {#ae4e7678c93bacb8b7806597a8520ca54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::insert (size_t index, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 317 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae4e7678c93bacb8b7806597a8520ca54">317</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="#a16362990092a086b505e08f102df4dff">length</a>()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ol = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;ol) </span><span class="doxyHighlightComment">// insert beyond end of string and fill gap with spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(index+s.<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memset(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[ol],</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,index-ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memcpy(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[index],s.<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s.<a href="#a16362990092a086b505e08f102df4dff">length</a>()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// insert inside the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.insert(index,s.<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a0842b6ab63d34f574d83e1f7d4e4f508">FileDefImpl::addIncludedUsingDirectives</a>, <a href="#abecd047709be2b8eda218b76bf9c385b">insert</a>, <a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>, <a href="#acffefc809c8b24e32df929c2985bdf48">prepend</a>, <a href="#a792b11db11f131e280229450e9ad4fba">prepend</a>, <a href="#a8270e394feda059b463a3588a41d6e5e">prepend</a> and <a href="#ab536413a2bab9fe536e82067a3f164ed">replace</a>.
</div>
</div>

### insert() {#afc8c31db7525ff4aab929f6526675689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::insert (size_t index, std::string_view s)</td>
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


<p>Definition at line 336 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc8c31db7525ff4aab929f6526675689">336</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#afc8c31db7525ff4aab929f6526675689">insert</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.length()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ol = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;ol) </span><span class="doxyHighlightComment">// insert beyond end of string and fill gap with spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(index+s.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memset(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[ol],</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,index-ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memcpy(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[index],s.data(),s.length()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// insert inside the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.insert(index,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### insert() {#a0acc09ca029c0a255063a7dc610be340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::insert (size_t index, const char * s)</td>
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


<p>Definition at line 355 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0acc09ca029c0a255063a7dc610be340">355</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a0acc09ca029c0a255063a7dc610be340">insert</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = s ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(s) : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ol = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;ol) </span><span class="doxyHighlightComment">// insert beyond end of string and fill gap with spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(index+len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memset(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[ol],</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,index-ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">          std::memcpy(&amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[index],s,len+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// insert inside the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.insert(index,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>.
</div>
</div>

### insert() {#abecd047709be2b8eda218b76bf9c385b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::insert (size_t index, char c)</td>
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


<p>Definition at line 375 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abecd047709be2b8eda218b76bf9c385b">375</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#abecd047709be2b8eda218b76bf9c385b">insert</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> s[2] = { c, </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight"> };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>(index,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### isEmpty() {#a621c4090d69ad7d05ef8e5234376c3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::isEmpty ()</td>
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
<p>Returns TRUE iff the string is empty.</p>

<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a621c4090d69ad7d05ef8e5234376c3d8">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty(); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::&#95;setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad5813e8f0f46839bf4f31d2f82789089">DefinitionImpl::&#95;setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a560d9d3845b99154c286dd6e50f0f934">DefinitionImpl::&#95;setInbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a93bbb9cd89a6d58d81a9796597e79fb9">HtmlCodeGenerator::&#95;writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::&#95;writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::&#95;writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::&#95;writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41e981742ff67fe146064ae772af3f72">SymbolResolver::Private::accessibleViaUsingDefinition</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3e6c42b51465b9d08e7e894fe3673b5b">FileDefImpl::acquireFileVersion</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8111356e211d82aed6baea53cda91872">addAnchor</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#a1dd9ba2dc2586e4dcd08ea7da6d93b69">Crawlmap::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a2fae83e2222326bc3e70dc7f3ada05d5">DocSets::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/eclipsehelp/#a9ea6d0cffe6ede5208e4d4079f54ea5e">EclipseHelp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a1503b3b4d76049d44a45452d44722d86">HtmlHelp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/qhp/#ad187b30da8187b859054c6271108b660">Qhp::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a207d66f561747d53a0df54a5019cc45b">addDefine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a745ab96a81d2f900d75b86848050a8a7">addDefineDoc</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#abf63a5af48b746aaa8638bfbb8d787b0">DotGroupCollaboration::addEdge</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aae7040ab38171d6666f314331a4d6335">FileDefImpl::addIncludedByDependency</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#af6e40a9b55ddf54aebef42114a99a861">FileDefImpl::addIncludeDependency</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a7b0a42da35d51f4e7f198975258cf9fd">PerlModGenerator::addIncludeInfo</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#af14459516bd2c63e2637f45b668fd676">Crawlmap::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a247f8e8a9f527f64cbd47875876ee62b">HtmlHelp::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab85e90fb1ce212b54481688febedbc09">LatexGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/qhp/#afdd0e586dc670e184d23bf80c880f0cf">Qhp::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3f637ddb83d1b6005eec5aefe8b84f1">RTFGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a70d9d3885e2b3e6a8587e6c59e02afa0">HtmlHelpIndex::addItem</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a424adbb16d98e3ef52a4229263c68aca">addKnRArgInfo</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae17a2241e72a6e7c6f2160f4c6ac8a7a">LatexGenerator::addLabel</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a5aad47028a6405798bd2bd1de4002350">PerlModDocVisitor::addLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6c177ac509924d60c71b820d39d28b9f">addRefItem</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a118dacc3a4f140d0321d4fb170c8e8f6">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af9360a554b5e9b817c991a39445e2b39">addSection</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a29d1f8fcda9166d21abaf8d785c378c5">addToMap</a>, <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a83c5141d20cfce3f391f36e0d9ace3d6">TooltipManager::addTooltip</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa48018d80bff3d0e37cd1ff67c5972f8">ClassDefImpl::addTypeConstraint</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a9f3ce7c21549a8e70e535371ef94aaaf">addUsingDirective</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#a0a0b44c02ff02fda01a1aa4f4fcbbded">SearchIndexExternal::addWord</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acb9600203ce6656264dca810825c7cb1">buildClassDocList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad716b06348a4b4d2f0909ed729c8db38">buildClassList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac808ed1ddf94dd08b95d1ee433e96359">buildDictionaryList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad0c3ffb33cd6ae914d3e4013f2f142a">buildExampleList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#af6acf966d7ed7500f4ab36fbdce70db0">buildFileName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb157ec5dd9aa56ca80abcf1fd5099f7">buildInterfaceAndServiceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbba640854380aad154effc800d8b63d">buildPageList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6c44f1592724165dbf7e5a36be496b5d">buildSequenceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a685b08b025bb0139299eb40a0704df31">buildVarList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4bd83121097f770a187192b054f59364">checkForKnRstyleC</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aefbbb766c678a158e56f49d59a20d8cd">checkMarkdownMainfile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">DocParser::checkRetvalName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#ab09e45c115a5beefe878b915613bd3a3">checkVhdlString</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a45411d390f8310e821828edefffa0759">FlowChart::codify</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ace27d46d07e19112fc6ee3411915c8ea">LatexCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#a370900ffa665f2d187c9d87571de2fdf">ManCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acaccd6e77d3f7f597669a7c541b623a1">RTFCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/lexcode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5a47760391ae7b0e270bd1de323be1e0">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aaf9011f7d4c2a48af197236c52d0a95d">codifyMapLines</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abc809fca2014e90fe0aee477a1964ed7">computePageRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acf309728fac71ec225044c1afe6ae9f7">computeVerifiedDotPath</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a839b20e50d87c76670f581293fa18b63">ConceptDefImpl::ConceptDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4a4f83dcfb4d9490aaf82e597940b27c">containsWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7d7c9238115c2656c20621678519cb87">convertToJSString</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5b6b9f769803f3b7fb05ee88eb8c4c71">copyIcon</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6e5984219541c97536c13b07baadb83f">copyLogo</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1e3ec8fc9a7cd41405fc0c2039b07b57">copyStyleSheet</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9203c86bf68f5df83a758b49fae64a1">correctId</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08216fc437af3c55e1b7ac51430744f9">Portable::correctPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac3000b9ef927fdbbdf460fcf5d1c712e">createOutputDirectory</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#aad65fb794eac705b1f9e896602c59bbe">deliverablesPresent</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a7814e5796402b44a7ee813a2bd5c23eb">MemberGroup::distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ac4ad900c3524f1e1451d26329e285acf">DocCite::DocCite</a>, <a href="/web-doxygen/docs/api/classes/docformula/#ae40d1dafb6c93681ddf0a9bc2e961053">DocFormula::DocFormula</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af41254fa358458e4e1a018477f5107da">ManGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9cd67715e9170630446cb37535f93ac1">RTFGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a894bfecdbda01b83760c93a6a6947b9d">HtmlGenerator::docify&#95;</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a69e6795499d9f7fb8867f5496c590e26">RTFGenerator::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea7b80127d86e6971ff8933e3e8ae42d">HtmlGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a76b121da3731e5fe9c3c68775e5d4152">LatexGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a884c87751b85f4a6cf6e965fbc0bec9c">RTFGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae32c0528c173d54061e225bb9ecac3d4">RTFGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a2a7db7045021961de35c39ea7e1deb40">LatexDocVisitor::endLink</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc9cf36e3e61b81df2b0ada024366806">RTFDocVisitor::endLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abb252c9c1a9af617ee975f211f3da598">HtmlGenerator::endMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0b59f6064cd7c974823fef0a48c49f37">LatexGenerator::endPageRef</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab12302548e6e1d509ac835b18eab004f">RTFGenerator::endPageRef</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac40c99ba15be25abad2d514413a088b7">endQuickIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aca2bba69055abb8a7a7ea9ce8ce7f11f">DocbookGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f9db23dee65e962246bc08bec382947">LatexGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac82e6d2bb73a007715d4ccf10552848d">RTFGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad860c94401483cee6345e6dd71bab597">escapeAt</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>, <a href="/web-doxygen/docs/api/structs/htags/#a459ba4c5a4e6d3308cee25b93448f0cf">Htags::execute</a>, <a href="/web-doxygen/docs/api/files/src/portable-cpp/#a1a05b42d6baa2f85ed112c8a7c67ac01">ExistsOnPath</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9f3bbbf9ecc3d8cf038de3a62cb6cb5">extractCanonicalArgType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4f2d544ac38e037f4572ce9163d17aed">extractTrailingComment</a>, <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#aa9dc1225d5dff26cbdf7521f3d2d5ebe">field2URL</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa28cb040180473ff3e2ef3e03e55cbcc">MemberDefImpl::fieldType</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac43c4867446413fa46a4d1140f40eb9f">FileDefImpl::FileDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#acd4ff9a433984cc6fb8e9b6f47284420">HtmlDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a72964fa569229687454f00fe4dc4ab45">ManDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a02ac65b43b4122de86989aed6d356df1">RTFDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a41b5f683e302b49a51ffc8f4199e6d38">TextDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6232960902cd961ee248851d0f5a189d">findFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5799cbe90654271460f7384c5c6f1a69">findGroupScope</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a590a484692d935d4850c7e6bce508d01">FlowChart::findLabel</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5aa9158e081cf448e0822afbb0ac760c">findMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a640bce791d53e83dcbd47f7ab01620e8">DocTokenizer::findSections</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af26edad163d89566e81dba54c3c85215">findTemplateSpecializationPosition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/classes/variablecontext/#aa4cfe2b318b52c33b4e28b5840275d85">VariableContext::findVariable</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a7656679a311cb6f8c5269ada7d1f8bd4">fixArgumentListForJavaScript</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a54cbf7f6b07bc8fe4ce7295e534c844f">generateFileRef</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#aef1d730d619e5441ab6206a8fd5b1a45">FormulaManager::generateImages</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a0cf2ae6bf35f920987bb1804a5fed8b7">generateMemLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a33b4ffef65928cbc0b426e79f93334c9">PerlModGenerator::generatePerlModSection</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>, <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>, <a href="/web-doxygen/docs/api/files/src/cite-cpp/#a883e572433098a2f3714d29ddc109fc8">getBibFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acfc81350dc516af20831bcb14d6788c2">getCanonicalTemplateSpec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aa09142ff1ca07603f8bb2150ce9ceab5">VhdlDocGen::getClass</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">getConcept</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad3269d7d65675a5e83889f4a98f5610b">getExtension</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#aa5d001d30e4d16855d3656989947df29">FilterCache::getFileContents</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#ae5b0b50b8f76945a89b6ef8761a332ce">getFullProjectName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aea75bbe69de2d8ff75d41a40df878894">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ab3b02c051abc4e2dc28d7abb654cf1e9">MemberDefImpl::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#ac5f1e3b27673fb0ab040a07469c29a87">ParserManager::getParsers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae052d7dcea3289dd204d8d425cf9d4c9">getPrefixIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aba6653be2d238e1fc793706547950107">getProjectId</a>, <a href="/web-doxygen/docs/api/classes/qhp/#a92cf5646fcf45cb7d2f9c75b61d63e23">Qhp::getQchFileName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac86cd7aa5ce2d8d62ce8d8ab3fc035af">MemberDefImpl::getReference</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">getResolvedNamespace</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#a5ea636b28660e85fc0dc3b8d9b6daf2c">getSubdir</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a55e833486416944421ab66c492453fe6">GroupDefImpl::GroupDefImpl</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a048c00592e372edb8bd1cd16389b57a9">handleGuard</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac6f2811c13f5afdc6966f8985ff9908c">handleInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ab1d3964259e415011918aade535b6fba">DefinitionImpl::hasBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a316fa2238d8daed582c65e0805337722">DirDefImpl::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4e1a986cedbc4e480499acefaf503cb7">MemberDefImpl::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad3c4f1381738a670a02398a8bbb75ea1">ModuleDefImpl::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#ad81bb3ba85d992b1571d9f4b54068fb2">PerlModOutput::iaddQuoted</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad23f7d576fcba6cc66edf702842a9d3">inheritDocumentation</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a50654e77279eecd43b0dd91cb21420e5">ConfigImpl::init</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a122070be7aebc9e3ab560b58fdd922c9">initDoxygen</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a7cad610aa745779c12a50c3dcf2cdf61">DocSets::initialize</a>, <a href="/web-doxygen/docs/api/classes/eclipsehelp/#aefada9c9b474d36ef9b771e2361c8dc1">EclipseHelp::initialize</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#aaf8015f456496f1510c8e8643f959376">HtmlHelpRecoder::initialize</a>, <a href="/web-doxygen/docs/api/classes/qhp/#a7ee6480507e32d9142ec04d4e499ae7e">Qhp::initialize</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>, <a href="/web-doxygen/docs/api/files/src/trace-cpp/#a94476ca22ba9fc237ecdad6bf2a4c5e8">initTracing</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad65dc2d081e8048a924cd1402e4399ef">ClassDefImpl::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2c00f8a07993d7c52997da55f8392fd6">MemberDefImpl::isBriefSectionVisible</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8a5218dcda2be9cbc949b95713dad49b">isClassSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa41ca3cde0467d35291f6d6a48be0c44">ClassDefImpl::isExtension</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aae351e4e8775385568dd3d77f52707e8">NamespaceDefImpl::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e975b2170ce769882c4bbb8f2cb8b94">isLowerCase</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a37a4055f986c73a8de48cd5d19bdd2dc">CitationManager::latexBibFiles</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a37bf597b522fe84aefa564de5b8489c2">latexEscapePDFString</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac0fd4772eabf2904003c3e2608882c80">letterToLabel</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1afec505ae6d03e654d11f3b6010a36d">HtmlGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aa00031a2d8766a111e037878b9b2f3ca">VHDLOutlineParser::lineCount</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6278992808df867a22fb9a6d41516fd2">mainPageHasOwnTitle</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/sitemap-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a539e2c5c670b530000917c0492e07850">makeIndex</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>, <a href="/web-doxygen/docs/api/files/src/sitemap-cpp/#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>, <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>, <a href="/web-doxygen/docs/api/classes/mapper/#aa80abfd581280947c7a3c5849b589465">Mapper&lt; T &gt;::map</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a95e2724703e8c0f7d753368ffc64d05c">NamespaceDefImpl::NamespaceDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a4e52d619e02e6a48b41aa65affcac398">node2URL</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a02024f4f45b1070b31d529c2f1307533">objectLinkToString</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ada58cb886cb5f74b40a96749a59eb8b3">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9872f2ebb33a85b7fff7268fee91a977">DocbookGenerator::openSection</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b206a0c1382df26146e64cde69d1085">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2ed70425e19b1b76c43d7c2fa497e289">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab3dc4aca49387c2801b733951162e52c">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af1963a24dee9df501c8f65d4cdc02584">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aad39609386bf77fe37c6e6a3861e92c5">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa9a4faa0f71f2de7b7d2dad36d9af4e7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a73cba6031502ee804823f22bceee63b6">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ace45195acd5464fbc29281fd8d44c66d">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af32530eae2ce36e648a925f28f1ca781">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ad97a4cc87fd1c7125305940cee54a064">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9fdd8ed53636e7e2acdc3e9a019cdd10">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ab86abe43cae0b8b54a28a23f723af5f3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a81236a6d08e29da34ec95bcc10aea214">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a7da6db1950d1eab0b3aad3535af34d9b">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41c844f5b9078d32e11a14b45b6f5c2d">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a32d07320992840cbb96459bd77cd9608">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a5a4e5f6aea094c66e6d152fd2962a128">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a330c52431e7c540fcea7901e74c70da7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a718bc15298af2003de3afb45ee5a9794">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a611ec420e06726e8061f4fe83c3f8a6f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aff3cb0ea5dd2ee90d238e8689a34e0da">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a70abcda93ed50a2ffbdacf0f1d973c39">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a91c4bac8e040dd09f551e84422be0330">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a75424e0d995411ada22517a0ae193b4a">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#afe433f28083f19e3e5d52d79f47cda34">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2993bfecac33a60da6408f79586b7da2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3c72fc623be48174c003bb47c523d6c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa547c49d64497e4774d3405b9cdcf7f1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a88217cd97b6eaa15a8c8f4a8c4757db1">TextDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a31e19a340fe2392303f138f3d0d046f0">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ad55bc41271c5cfa6920f32fd8142ce31">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac219ce4773970158e118d1d3b57ebd78">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4f27cdc13bc0c7d51bbc657f000b29f4">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a0e8bc2ce89c9b20a8b9879393aa6108f">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a11012240cba58c78041715a6c963b350">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ae2f1f49b8496f09377c4e7de91e2f3d6">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#acd694108a8abefd6d6d7be9c7bba21cc">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a73f1b078fd79fffd3a50ca217b580bed">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2907cfb329df93257c355ceaa29993d7">organizeSubGroupsFiltered</a>, <a href="/web-doxygen/docs/api/classes/translator/#aeb959325f8c633c58336870b4d0504fb">Translator::p&#95;latexCommandName</a>, <a href="/web-doxygen/docs/api/classes/condparser/#af254c02cc742b034cf62a9846b7b9749">CondParser::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/lexcodeparser/#a907e618c99ef07aa00fc0604062e3929">LexCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/sqlcodeparser/#ad4cfac05d7a0c2354cdb90992b1e0248">SQLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/xmlcodeparser/#a1e7283cd50a9220c8381cbdf953702ca">XMLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#af8538fc61fb952e7681b9804247edc13">DefinitionImpl::pathFragment</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a001e5e4b6b99ed83d3333cc3adf5afd2">printNavTree</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abafe8d30316505f2a4c60ec608437ebc">projectLogoFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a1cbb9db483a1cd53acc3671d25399cda">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfb0efa72e3e5ed08b1881ccd8332e5e">readFileOrDirectory</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">DocParser::readTextFileByName</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#a150d4d51073cb46cdf38a236cc120d0a">ParserManager::registerExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a5f5bce72519f9278f849a2c4cf936393">CitationManager::replaceFormulas</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acbd23ce837bcb562fbf5909c28e3ee06">MemberDefImpl::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa143df64f11eae89ec87066a67e0593f">DefinitionImpl::setBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/private/#af8a551d5ba6e33523a40c372ec854203">DefinitionImpl::Private::setDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ac5533bd798e00c23bb4b0532b036ea8b">DefinitionImpl::setDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#a3d9eb667db4f11f9bd15cfc0b8fe45b4">setDotFontPath</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#abd244447df22d110ad410b69c357fdf3">Portable::setenv</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a38a736137370a011fe71a0fd9102d151">GroupDefImpl::setGroupTitleLocal</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a70f7bf525b5632c2b87c7f1a5695a5db">DefinitionImpl::setInbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa503fac344494b18daf0891af92159aa">ClassDefImpl::setIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#ad2150512ed4558c1f2dc267555f0c0df">ConceptDefImpl::setIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a065cc165c287399167d790bd59ac60e0">MemberDefImpl::sourceRefName</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab575d0e0e347d711d242bdc7fd8c7648">DocbookGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a53fd55ec2cf65b5c1843b3e1925f2cad">LatexGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7a82873f4a7eeacb88ef535768b311f4">DocbookGenerator::startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a80da85d198868bc3351b1a6a90f32a75">HtmlGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac5c56d415b19f1c6eb2531cbd238d920">LatexGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a32ae4842f51bff5b91ddb9f00815ddb0">DocbookDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5d0952f3540fc3f94da3fca8dab4ba23">HtmlDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a7622ffaad8b1168ffc837eae842d6c53">LatexDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a02328f0a76dfca6a9e0d24167905289e">RTFDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a5fa013b821ca9681befa4786b6877709">XmlDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#afcd6c1e555f2bc462f5703468b23c3d8">LayoutParser::startMemberDeclEntry</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a159d9ffd0d6742275e763d2bb25ae3f0">LayoutParser::startMemberDefEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a477b9bf180d9c7a57edcd11c408cdb5b">HtmlGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1ec800447787c1eada0c828c6d3bb374">HtmlGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aba3b3876764867eeb32b9dcce3d4b63b">LayoutParser::startNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa39c36a133f69ff84e4d617e3915f9c8">startOfRequiresExpression</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9">HtmlGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a191128ce8eb169f11064b884972f2ec2">LatexGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a775d9cad2024f07bb3e760e86e6267d4">RTFGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a607223d8bf91989cb35218acc2b95e3c">startQuickIndexItem</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a3a78c06f8d054ac9c9b0b210d243f9b6">LayoutParser::startSectionEntry</a>, <a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a68725c575a9ec30586e5c67a284712b6">LatexGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a46e5dfbc859151dfe39ea12ec75a5c13">RTFGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>, <a href="#a6444196e54d0b736cef5c9edd8c262d9">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#aad3d1cd78282b91d3a5d5c91686cb13b">stripProtectionPrefix</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9fcc3d0c9d7df5c8cfe5b43686e52e1a">substituteKeywords</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#aa96df86060821bfa919eb9ffd8283064">TranslatorAfrikaans::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorarabic/#aa9b71f55a44e8ba730adbee20a324bf4">TranslatorArabic::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorarmenian/#abd9b93b73f9fb7128f9d562fad7ef677">TranslatorArmenian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ad65187b566fba148faa8e0f9834f5853">TranslatorBrazilian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorbulgarian/#a2ea38b83c20b6fa498a07f72dc6bca81">TranslatorBulgarian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#a66eca5c3135097f1ac4b93e5c2ab9cf3">TranslatorCatalan::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorchinese/#ab8bd5fff78224d562432f6ad4c6f8b03">TranslatorChinese::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorchinesetraditional/#a8e98c64ccfdad8ffbf170d3d5054a6c7">TranslatorChinesetraditional::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#a4d61bfda26969d13d0ba61b905c22c33">TranslatorCroatian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#a25eb21dfd47c79569a08a5ed88474ad0">TranslatorCzech::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#a0bbb45a0108effd8d6d968d370bacd6e">TranslatorDanish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#aa8ab8849e4afe6c9232e18a32a23dfbf">TranslatorDutch::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#a08d515faa450f99cdc24d1ddfe702647">TranslatorEnglish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#ac746b45b8dc44b0038562465048c3b09">TranslatorEsperanto::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a815bbbb972ce25846070b47dd2e72138">TranslatorFinnish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a6761574c25eb5d0570521489729b9574">TranslatorFrench::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorgerman/#ab6b890e46cfca9c6d456e27aed055020">TranslatorGerman::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorgreek/#abac22e612b99db7a0d432559adbad38e">TranslatorGreek::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorhindi/#a404d7200a4bedc59048359d60399f130">TranslatorHindi::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#ae94eb9c1255c12819325f30ef127b860">TranslatorHungarian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorindonesian/#af0f62a0d45ed4c031f8f217adafa20ad">TranslatorIndonesian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a1e3dd4fafc4fb273ad1dc4bb9e5504f1">TranslatorItalian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#a2e59e1c2fee86be74b515f4bbd8b98d9">TranslatorJapanese::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorkorean/#abad2ed3d899dde75dbfd9e66eef08b45">TranslatorKorean::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a6a5f92cd9abcbf0933433434d679528e">TranslatorLatvian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#aed96d80e686acf49dda26fff54bbc2b7">TranslatorLithuanian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatormacedonian/#a82bec46a26ff51ef3a79e690b3f55d4f">TranslatorMacedonian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#ae681c2bc3abda5885bc09de1a34a336f">TranslatorNorwegian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a629958eaeffa29e29406e17a085954bf">TranslatorPersian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#a2569abc44c4e51f2f3407e8b3c265328">TranslatorPolish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a1b8bc7b78ee9aaecb453faa6779583cf">TranslatorPortuguese::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#ade10ce86b91d43f96c6a1da75d6c774a">TranslatorRomanian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorrussian/#aff8c74421f75f0de38a448cb89b570ff">TranslatorRussian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#aeb948489414667dcf2122d4fc15088ab">TranslatorSerbian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorserbiancyrillic/#a6b3f4fa0ea9ba45bca3d111d2c87c555">TranslatorSerbianCyrillic::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a465d1ce89c4041ce43bccc91321c1651">TranslatorSlovak::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#aa0343839da0337461e99ec62cff7efc3">TranslatorSlovene::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a4d744ac03647ba20d05b5369874217b9">TranslatorSpanish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#a1f4b6ec1eeda7f4f2ce6d950b03b2baf">TranslatorSwedish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorturkish/#a9f5a44c88596e72f26d4042bfd20a2aa">TranslatorTurkish::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorukrainian/#a09d56925504ae19ac334c7003f2805e5">TranslatorUkrainian::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorvietnamese/#ad0cc7710772a62fa9e5beb09dbcf1b74">TranslatorVietnamese::trDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a3d9b7aad40a8c81882fef56ba6d78e57">TranslatorAfrikaans::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorarabic/#a8e862b1e1a1d7fd0fd5c40bdbf0640b7">TranslatorArabic::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorarmenian/#a55a3f05de9b2c570a18769b014c0c203">TranslatorArmenian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a8f5a99fe476c6f857086cc418879e35f">TranslatorBrazilian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorbulgarian/#a54616bfadb4ddec51c889bf942c87d5f">TranslatorBulgarian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#a70f1671122dbb56863d2d72ee2e998e5">TranslatorCatalan::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorchinese/#adde442e745ad34fdb8b1882930be2ed0">TranslatorChinese::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorchinesetraditional/#a6fd2d4bee2a79e1d02d7b5efc020baf8">TranslatorChinesetraditional::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#a1f92976e359a258a022e86b0790def7c">TranslatorCroatian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#ac1039ac32440e9bbd8c5d98971bb9f31">TranslatorCzech::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#a6cb7226f702c308de5a3eff4bd5a7d57">TranslatorDanish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#ac19a30b5fd4a8d305fadeb1984f15517">TranslatorDutch::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#a0aeba00102fb7002ba1846baa7b63acf">TranslatorEnglish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#aac0a352e9a5755cd182fdb8959043022">TranslatorEsperanto::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a7312294ee0baae51cd3865488e6622b8">TranslatorFinnish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a38bda871ffc0febc0abc2ceaed0b9bc9">TranslatorFrench::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorgerman/#a8b7bc6b1ffe65f7a8162220f9d1686cb">TranslatorGerman::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorgreek/#aa797cfc2af778d2be132158bfdd1dc6c">TranslatorGreek::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorhindi/#abc8c2a158852105aecd31961140796b1">TranslatorHindi::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#a3ec1a655b99fb27ba7e8b8a5c9b962c5">TranslatorHungarian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorindonesian/#a03d4c4a09a803f56becd66c45328d8df">TranslatorIndonesian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a2f4c92350347a5effc50df5846b6712d">TranslatorItalian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#ac1ab0b21c9a279a8837a705fcb435d5c">TranslatorJapanese::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorkorean/#aa9a676e0690d757e6e723d6712defe00">TranslatorKorean::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a75fd138d3cafdd667cead4b8056eb497">TranslatorLatvian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#aafb31ef31267df75cd9a707d8362fa9b">TranslatorLithuanian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatormacedonian/#a5752c3357edc8ab42110816b5ace0f65">TranslatorMacedonian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#a4d3cdc6aa06eefe9a7e7f9b9ae19b210">TranslatorNorwegian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#abd5222c2f1b5e5a858f8b13d318dba7e">TranslatorPersian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#ac9f3f714e079590febd98a5911cb3cf3">TranslatorPolish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#ac7ecadc6654ac7dd80215cfea0be9dce">TranslatorPortuguese::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#a7f429479f14105c221a0ea89be5cf283">TranslatorRomanian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorrussian/#a5d7fd3e2f4e45bcfce8c221dbc03e9bf">TranslatorRussian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#a8b846a3b8b2fcb912d6ef94fb85dd0c4">TranslatorSerbian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorserbiancyrillic/#aecb9dafbb07bd3c06d498872bff76487">TranslatorSerbianCyrillic::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a62e6faeffe248b19e8328ac4acf4e91e">TranslatorSlovak::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#ad4eedd7efd01f2a5cb1af450d5fa3da2">TranslatorSlovene::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#aabd403b678635dcdda966a7f2d32a6ef">TranslatorSpanish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#ad2c4bcefd2e34ccafc23da613935bcad">TranslatorSwedish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorturkish/#ab76a90a905a13cad08fbb7deb0d8b6f6">TranslatorTurkish::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorukrainian/#a09c7cf73180509e5a98deb0b094c57d8">TranslatorUkrainian::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorvietnamese/#a0cc0169a56cb66fab956dca77bcb5ac4">TranslatorVietnamese::trGeneratedAt</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#afe140c6d4ac2d2967bae76fe4aab7dd9">TranslatorAfrikaans::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorarabic/#ae667144a934afa76baeea0d2f4a41965">TranslatorArabic::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorarmenian/#a2278ebb2d70b7d3d8b0c8a893b71832f">TranslatorArmenian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a46c707119dce865a87a65a08bda2098d">TranslatorBrazilian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorbulgarian/#abe76047a2a91721e9ce8e5761ca9d610">TranslatorBulgarian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#a07aa3d3ab8f80f82b50a8d2c2f8899d9">TranslatorCatalan::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorchinese/#a37043399d48389168c03bf9485342791">TranslatorChinese::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorchinesetraditional/#aea924f8dcfa808d79f32ca7747793d41">TranslatorChinesetraditional::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#a71d72bc68e0e39078e65a5d1dac0c8eb">TranslatorCroatian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#acc069dd60e0e1f329980af6409e71368">TranslatorCzech::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#abc2418a2dc685767852b71aa18df8d13">TranslatorDanish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a4a80ae0c0acc8506526af973f965e457">TranslatorDutch::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#aff520112f4dec310c5ce3017a6e9c8c8">TranslatorEnglish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a64ab4583d07a077e1661369067a03c77">TranslatorEsperanto::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a1523a73219aeca7b2d37c45364ff65df">TranslatorFrench::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorgerman/#a8dde684105a8b2df42b35e014f9720a5">TranslatorGerman::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorgreek/#a0832fa894427f30aadf7387b0372b2c5">TranslatorGreek::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorhindi/#a54ba79541e7d4eafe64e6500501f4ef2">TranslatorHindi::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#a283d90f114ad1cbd7cdde580277c9c0b">TranslatorHungarian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorindonesian/#a6bc50a3a1a7c6b6909c5e33e1d1629fc">TranslatorIndonesian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#ae05d2be268bebabaf7ddd6e41948b811">TranslatorItalian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#af6bfd02a4ef0009c2755f4577e94a2c0">TranslatorJapanese::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorkorean/#abcf153a268f3224636787c76e3756126">TranslatorKorean::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#aa614b8ac909af3bf01e4696776dd6e0c">TranslatorLatvian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#ae7cc2097573214dccc633e91d62f308b">TranslatorLithuanian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatormacedonian/#a840b128e0d96fefed119e4f3a4f0098e">TranslatorMacedonian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#a6a119ab4048877973798fbf8f1241791">TranslatorNorwegian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a6437e341774f0bed5679ca32d7dfa562">TranslatorPersian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#a45deb98bf9a17249726f99577869cbb4">TranslatorPolish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#ad84ec4ea54797fb937aba93444f29d27">TranslatorPortuguese::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#a8d12aab88823224f8a505ee8593558cb">TranslatorRomanian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorrussian/#ae12ef21d06409c21bd6fd3fb45109ab5">TranslatorRussian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#a69b5f66284c22924acb0655a7b5fe79e">TranslatorSerbian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorserbiancyrillic/#ac5745260fa94b2e6077616fef3cb67f8">TranslatorSerbianCyrillic::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#afa9cdb4bb85072cf0d89ca99acecd525">TranslatorSlovak::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#aff9e332c4615abee110e155502ee1987">TranslatorSlovene::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#aae7033b0f11846651ada670640ee000a">TranslatorSpanish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#ade791358d8d2c24f7a2be49488986b9a">TranslatorSwedish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorturkish/#a5ee0e356d238fedc11b30b169235c7d0">TranslatorTurkish::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorukrainian/#af71dd94afb7865babdce2b93bd7d5396">TranslatorUkrainian::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorvietnamese/#a08bf5e43fe94b00d96bbc358d58bc44a">TranslatorVietnamese::trGeneratedAutomatically</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a67d1a2718cdc469a31be735783e3702b">TranslatorBrazilian::trModuleMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#a2716b6684322c2cab0b8294ad354950f">TranslatorEnglish::trModuleMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a9c123c487354d1da4ce2ac45063b37ca">TranslatorPortuguese::trModuleMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ae1d5221621a7b488452448dd357954ab">TranslatorBrazilian::trNamespaceMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#a61d9c92550deaaa92c1b38508d4ef4a0">TranslatorEnglish::trNamespaceMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a7999fe3e30ba54722fed6e7c5d0d8e01">TranslatorPortuguese::trNamespaceMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a3bae1ebb5930767ed2f85f3d64bf0bb7">TranslatorSpanish::trNamespaceMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a75237d30f908ef839f400a0fe7584f9a">unescapeCharsInString</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ac2e29048cffc72c3bed439cff5b02cd4">Portable::unsetenv</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>, <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0c4f7806424406a4dddeaf5c916abb5e">DocbookDocVisitor::visitPreStart</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>, <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#ad2b918f141b60e444314ae661cf02162">visitPreStart</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a4149b6b3cb3e0246eb2e0d47de02538f">warn&#95;line</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a31cfb988a49ee5b4f6e0f64dded34507">MemberDefImpl::warnIfUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a95bca7ae1fd2732e74c0ce749e76916a">LatexGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa7ae50a52d4e01f107667b89ead7b3a3">RTFGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#aeb01acd1ef9dbeb87e35e7eae24143b1">DotNode::writeArrow</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ae073efd8b440046f245aaff6c56bc1f4">LatexCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/mancodegenerator/#add59fcdb30edd4ebfd1b0da8787e2e52">ManCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a2d50b342c2ca0801234fb76838f7e880">RTFCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#adb92a04549bb311fb043a2d4ca4a0a7f">writeDEFString</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afb6a683a89f794ddafb8f8fd1cb55fc9">DefinitionImpl::writeDocAnchorsToTagFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#af17ba3b2d4018a62fce735ce6c69c277">writeFont</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">DotGraph::writeGraphHeader</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8961a6e2496115a7cde0222c4ee213d6">writeIncludeInfo</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ae3e188b81cd05fbb4e12621850e7d5e4">DocbookCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a87bd505cf0e4598b8e8ae320087166f3">HtmlCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#a41b0a17952879ed6de614c8bd4ff6c9f">LatexCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#ad7fd3e3cc19d62798aa65d318a42e47c">RTFCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#aac332610fed5a983f3b5e012c1fcddef">XMLCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl/#aeebc63bda55bc226c43f72d75e1e92a4">TextGeneratorSqlite3Impl::writeLink</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a52015628829279296a6334d955676868">writeMemberReference</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a1a9fc7a255fa7160711dd47a9de1695b">writeMscImageMapFromFile</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af173fc80e34a6372764c46d3cf4c7758">HtmlDocVisitor::writeObfuscatedMailAddress</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a46e18e094779f6af393deafc4b64d454">HtmlGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9af437de0126be35d936123ca8eff51a">HtmlGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aa9cc3c4f52d431fc6a5d4940c6fc0ea3">LatexGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06cb016c789f240eabead87f1a10325a">RTFGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/image/#a9548b8956604519c4260cbdaf7854792">Image::writeString</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abf222cd6347aaf899d714dae6ddeb52f">HtmlGenerator::writeSummaryLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3d1a9e0be346811184a93c9337e12f93">ClassDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#ab7a2edfc61d2a8dd5c068968655070dc">ConceptDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a8c0d8e8ebfd5536cead696b584ac6e">MemberDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a57b6528e8c47fc04f0ca3aa71fbb1dcb">ModuleDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4bbc6ca08fcd6e9ccbfd15cdf3bfbf1d">NamespaceDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a0c852a5df0dd82d83c4ec8b99f4e3937">DocSets::writeToken</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#ab450dd921a83f6ef2535324349f6f1c1">HtmlCodeGenerator::writeTooltip</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#addab75b1cb249ffe90ab4624fe4aa530">writeXMLLink</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>.
</div>
</div>

### left() {#aecf8b66312c4e97333219cc344c11a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::left (size_t len)</td>
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


<p>Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aecf8b66312c4e97333219cc344c11a4f">214</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#aecf8b66312c4e97333219cc344c11a4f">left</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty() ? <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>() : <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.substr(0,len));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a662691ab2b83958aaa9bdddb1a974c6f">MemberDefImpl::&#95;computeIsConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::&#95;writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::&#95;writeReimplements</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a2b8e4d926adebd224807ed5d9f0e3192">addCite</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5a47760391ae7b0e270bd1de323be1e0">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a717f9e550bc2df9508126b7cb4dd23c3">demangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#aa0944a06a26c8f552be061cd5060baa1">DocInternalRef::DocInternalRef</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91b99c5ed2e4b31b81c9eda9514c53da">extractClassName</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa92d2aaaadff51d927a9629cdad82a9">extractNoExcept</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a5cba77d157c52ffaef77df9fb2782230">getBaseNameOfOutput</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#ac5f1e3b27673fb0ab040a07469c29a87">ParserManager::getParsers</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aa2b4c58062de6e3075936abc6c29dd7e">getTemplateArgumentsFromName</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a01336ef49f88d4dd7f574c3db13ad774">isCastKeyword</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9905c57ded9f8f4db3bbe658e510f781">MemberDefImpl::isDocumentedFriendClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0947f1f8c60660017b41863e47fc61be">isRecursiveBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">DiagramItem::label</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a373928f3b61089f84cb4ee946474792f">leftScopeMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a52cc252e59332d38e224e11bd019f632">matchCanonicalTypes</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad091d341c14ea4fbd41ca45921d5b75f">mergeCategories</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#abc751e8cc79b9f7cc8040ba7ecce6e1f">DirDefImpl::mergeDirectoryInTree</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aa32a03da6438377d962da12f57b0f2c0">VHDLOutlineParser::popLabel</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abafe8d30316505f2a4c60ec608437ebc">projectLogoFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#ada088a153d3ab756e5be8bd628b10e9a">splitKnRArg</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a67e22ceaa05ae493f2f3892681aec351">splitString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5b4fd5c937a0d1bb806033635f35cc99">stripDeclKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a1d6f1eecdbdd686db90d37c6636f12e6">stripFuncPtr</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a15f807d04ca6a15d183d7c05396bae30">trimBaseClassScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a0332e2befe926de95b367c391a0ac70c">DotNode::writeDEF</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a4be56bbbeefd5d44b58d28f05c446725">DotNode::writeDocbook</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a0c852a5df0dd82d83c4ec8b99f4e3937">DocSets::writeToken</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a1cb314bd0d605efa7019319e3da26870">DotNode::writeUrl</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#aed2051e58bce93b9250b99108a77ae00">DotNode::writeXML</a>.
</div>
</div>

### length() {#a16362990092a086b505e08f102df4dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t QCString::length ()</td>
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
<p>Returns the length of the string, not counting the 0-terminator.</p>


<p>Equivalent to <a href="#a957be37e3b98707fc7e8daeff18e391b">size()</a>.</p>

<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16362990092a086b505e08f102df4dff">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a16362990092a086b505e08f102df4dff">length</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size(); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::&#95;docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::&#95;setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a93bbb9cd89a6d58d81a9796597e79fb9">HtmlCodeGenerator::&#95;writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::&#95;writeReimplements</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ab657e2797fb2f8d57ca202215fc2003d">FlowChart::alignCommentNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#af6acf966d7ed7500f4ab36fbdce70db0">buildFileName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a7d789071ce6a6464fb8ce89eb65083d3">charsToIndex</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7b984704d9d6ad6819140f993d6bce4e">checkExtension</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#ab09e45c115a5beefe878b915613bd3a3">checkVhdlString</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acf309728fac71ec225044c1afe6ae9f7">computeVerifiedDotPath</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>, <a href="#ab2617e8fdb6c52fb762a52f7252d61ed">contains</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a7df6021b8c7a5e9d81c3e586bea19a25">TranslatorPersian::convertDigitsToFarsi</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a20350e5803a50856a69419c6473dd5a1">MemberList::countEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac3000b9ef927fdbbdf460fcf5d1c712e">createOutputDirectory</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#a7dbcc0b3d8792f7eb24a5586609bd020">DocAnchor::DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#aa0944a06a26c8f552be061cd5060baa1">DocInternalRef::DocInternalRef</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8d91af0a6807cf2a6b66896bfdef6732">encodeDirName</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a>, <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a618f6f860ec6268437b3e44d313d1f87">escapeId</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3a1173b85597fdb88c5bf3f6d7f9e024">extractBeginRawStringDelimiter</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ac494d47958d1f5413e97e355624ca8db">extractBind</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a6de6c67e6bcab57266d337ac0ccc26f2">extractEndRawStringDelimiter</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa92d2aaaadff51d927a9629cdad82a9">extractNoExcept</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4f2d544ac38e037f4572ce9163d17aed">extractTrailingComment</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="#a0182ece6b76dad6475dafb53e2faaf10">find</a>, <a href="#a5381d8547e101adef3ee87f8d54c9925">find</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a019e4dfdc4fe1a34460b8f7bb8dfe0fa">findEndOfTemplate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>, <a href="#ab6cbf7f8b8943606766d6e3d2e26fc70">findRev</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af26edad163d89566e81dba54c3c85215">findTemplateSpecializationPosition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2086de9221c9c0a17efc40915a054852">generateAnonymousAnchor</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acfc81350dc516af20831bcb14d6788c2">getCanonicalTemplateSpec</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad3269d7d65675a5e83889f4a98f5610b">getExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a9b5774d3b3547b5143e86594853498">getNextId</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad7fe83480a1c139afa09ab1183da5ca5">getParserForFile</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#ac5f1e3b27673fb0ab040a07469c29a87">ParserManager::getParsers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aba6653be2d238e1fc793706547950107">getProjectId</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afd249e264b966d05a54b740e3d43ad6e">getScopeFragment</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a710af507a150913251c3885189b77fb8">isConstraintFile</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae604f9461d7685908488ead7a6d72ca0">DocImage::isSVG</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">DiagramItem::label</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a373928f3b61089f84cb4ee946474792f">leftScopeMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0a8299ea0705cebde431ef0ea600fcb1">DirDefImpl::matchPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/files/src/defargs-l/#aac9470d1061fbdc10e05184c45712c29">nameIsActuallyPartOfType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a7910d0ac9f615f9ce451bd0c71d15da6">VHDLOutlineParser::oneLineComment</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a7da6db1950d1eab0b3aad3535af34d9b">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a315f64205ff8e9d75ddd63e31f068269">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a88217cd97b6eaa15a8c8f4a8c4757db1">TextDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53f751007ffe5b7c105c3821039a970c">processString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#aff805b06ccfab10b895659c51afb5829">DocTokenizer::pushBackHtmlTag</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3f2329035cfde039380d267efff68c76">removeEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a653335defbae0c2b319413c2d9376458">resolveUserReferences</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae0c5a702c29f403e331441abfe289d5b">rightScopeMatch</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a931044da5493c1d83ca77898996140c4">MemberDefImpl::setAnchor</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a45928a3aa04b29c259685a5d3f6cbf4d">skipToEndMarker</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5935e8ddff8337f8a43689e2713c8067">ManGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a544c6fd0814756e0e4ab69eac035ff7f">startsWithKeyword</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a085c52ce4351470497b03309e77228cc">stringize</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a3a30de88958d15c2cf424f7efc5c6ef9">stripAnonymousMarkers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a1d6f1eecdbdd686db90d37c6636f12e6">stripFuncPtr</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78d33655f54cd45e22070b58a6dce6b6">stripScope</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a255ee5917ab88a261843376db88293a5">stripTemplateSpecifiers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae81df9187a70102c6f47ca6c2c5012f4">stripTrailingWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>, <a href="#a524e1cd9e1c24e91d57b1cb91513fa67">toUInt64</a>, <a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a15f807d04ca6a15d183d7c05396bae30">trimBaseClassScope</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#abf1c2318a734ffb00d9d128e83cd0e7e">TranslatorJapanese::trWriteList</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ab8df06c9b8d04453c03cd380baa8e0b8">DocTokenizer::unputString</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ac0d4a8f26f5daff4ffb1702f24b35697">DocbookCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ae073efd8b440046f245aaff6c56bc1f4">LatexCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a2d50b342c2ca0801234fb76838f7e880">RTFCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a22f6ad09446c1965714f48e8cbf8459a">XMLCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ada73fe6def10a3e449256fc96929e8b2">DocbookCodeGenerator::writeCodeLinkLine</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a0b6667c7bad976edc1ef63202c87defe">writeString</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a84a2aa61638b8af08560219e2a5140f1">ConfigOption::writeStringList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a0c852a5df0dd82d83c4ec8b99f4e3937">DocSets::writeToken</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a1cb314bd0d605efa7019319e3da26870">DotNode::writeUrl</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>.
</div>
</div>

### lower() {#a33688239622e659cfb469fbd62c9cccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::lower ()</td>
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


<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33688239622e659cfb469fbd62c9cccb">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a33688239622e659cfb469fbd62c9cccb">lower</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aae48ed44191778c99e285f17b7e14377">VHDLOutlineParser::addLibUseClause</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ad36e56c8bfd19605777cd5511cd13cbb">addLocalVar</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#abe42707109ca3bbad6ad388f766d8218">DocHtmlCell::alignment</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac191ad1786e980d514c4535505cf99d6">checkFileName</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aaf9011f7d4c2a48af197236c52d0a95d">codifyMapLines</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a2904843bbc4e5d707386d5dce049692e">CitationManager::find</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#adfe5e615942afd900cff9f219424d5a5">generateLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0ab63cb2f20e16fa82b9b687d2b4b00">genericPatternMatch</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#ac5f1e3b27673fb0ab040a07469c29a87">ParserManager::getParsers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ebe50fa5f3c75360a5fcfda16fd0317">handleFileInfoResult</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ca04f9cfa633f92d16cdab66a3635db">handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac6f2811c13f5afdc6966f8985ff9908c">handleInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2dd347b6be51aa404a4e6bc679736606">MemberDefImpl::init</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#acbc101ba2926c6324a479b572ff3c377">CitationManager::insert</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aca89c5ef98d812439cd931a762b49213">keyWordsFortranC</a>, <a href="/web-doxygen/docs/api/classes/mapper/#aa80abfd581280947c7a3c5849b589465">Mapper&lt; T &gt;::map</a>, <a href="/web-doxygen/docs/api/classes/coutlineparser/#af11fbf8a139c8880d6b6cb796b9c882c">COutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#a715ceab8e5e5c872065367e3f88c0df5">FortranOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1afbc68aaf494a718c743d508b394a83">DocHtmlCell::valignment</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a64ea38c6553eebe39c034c704bcc2eeb">writeColoredWord</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>.
</div>
</div>

### mid() {#a27136caf9c0bc4daca574cda6f113551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::mid (size_t index, size_t len=static_cast&lt; size_t &gt;(-1))</td>
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


<p>Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27136caf9c0bc4daca574cda6f113551">226</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a27136caf9c0bc4daca574cda6f113551">mid</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(-1) )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> slen = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(-1)) len = slen-index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty() || index&gt;slen || len==0 ? <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">             <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.substr(index,len));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::&#95;writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::&#95;writeEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a29d1f8fcda9166d21abaf8d785c378c5">addToMap</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aac61019f2270df6f5bfa4efed4760845">ClassDefImpl::addTypeConstraints</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aefb94fa4d5f207d7a1aa6c7fb5ab54b5">convertFileId2Var</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a2634e192e6fb1db99bb22fb62a9e8c0f">createJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/portable-cpp/#a1a05b42d6baa2f85ed112c8a7c67ac01">ExistsOnPath</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3a1173b85597fdb88c5bf3f6d7f9e024">extractBeginRawStringDelimiter</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ac494d47958d1f5413e97e355624ca8db">extractBind</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a6de6c67e6bcab57266d337ac0ccc26f2">extractEndRawStringDelimiter</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa92d2aaaadff51d927a9629cdad82a9">extractNoExcept</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a08d427ab614e1a8142b07a629730673f">extractPartAfterNewLine</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad2143a92408c0b36271fbf7dbe84f4f7">findParameterList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad3269d7d65675a5e83889f4a98f5610b">getExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ca04f9cfa633f92d16cdab66a3635db">handleImage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa41ca3cde0467d35291f6d6a48be0c44">ClassDefImpl::isExtension</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae604f9461d7685908488ead7a6d72ca0">DocImage::isSVG</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/sitemap-cpp/#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ad4ef2fd3be12660847c709847af5d620">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ad4ef2fd3be12660847c709847af5d620">makeShortName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a52cc252e59332d38e224e11bd019f632">matchCanonicalTypes</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a4e52d619e02e6a48b41aa65affcac398">node2URL</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a6185cb6e624208c3f4ffc97ac506b992">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a7da6db1950d1eab0b3aad3535af34d9b">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a88217cd97b6eaa15a8c8f4a8c4757db1">TextDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/filecodeparser/#a16bbf3ac1b836ae70528f1d9ecd11e6a">FileCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53f751007ffe5b7c105c3821039a970c">processString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa50164ebc8d5c581d278e1d0f7f2ca54">removeLongPathMarker</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a5f5bce72519f9278f849a2c4cf936393">CitationManager::replaceFormulas</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#ada088a153d3ab756e5be8bd628b10e9a">splitKnRArg</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5b4fd5c937a0d1bb806033635f35cc99">stripDeclKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#aad3d1cd78282b91d3a5d5c91686cb13b">stripProtectionPrefix</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4025119712ca93c25aff95e1f4c9a344">stripQuotes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a301116112cb06af3d6fa71fdb8c9b940">stripTrailingReturn</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a8fd031de6dc372d115ffd400a079fd19">TranslatorAfrikaans::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ab920c6c849cbe6ca181cb7efe4d1d8ef">TranslatorBrazilian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#abeb7cee64d567513c5b6244cf4a431ec">TranslatorCatalan::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#a09a17e262f3b2e90b2c55605f6dc5219">TranslatorCzech::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#a977499d4c707fb5913baf8871869e96a">TranslatorDanish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a587d06a96240ff6a61ed1b8a33658f3a">TranslatorDutch::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a90f6875eb086e11dc144f69690bee9f4">TranslatorEsperanto::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a205d35db17367515b7aca6d451885e5d">TranslatorFinnish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#ae226daa02d58dd042ca5f77a90f222e5">TranslatorFrench::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#aef452b564046eb574852739e89d8eb43">TranslatorHungarian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a3341f96ed21e91bd45ca5fd1314f4dd0">TranslatorItalian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a2569649d9fe65ec604548acdb0f6226a">TranslatorLatvian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#a1ee6c826869f34abbcdc132ecb44f849">TranslatorLithuanian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#accac5d3afb97530bb7039ffab1af0f87">TranslatorNorwegian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#a03f0a4b1a2cc89f81e524bd38dffd836">TranslatorPolish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a5d2bc6da7ecde60b9b361e27ba2175da">TranslatorPortuguese::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#a3cb0de7566c1f2ed6699d4ac4de373f4">TranslatorRomanian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#aeac9ab8b6a97959e4885fb2c65ae7bdb">TranslatorSerbian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a2f3e0c4664e0608a5060d24b13d0a61c">TranslatorSlovak::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#a97f9768906b403c9c74a7a693bac7a30">TranslatorSlovene::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a4d9965d2a03082b81ffe81f6c99d02e3">TranslatorSpanish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#a48da7d6eb2bde4dca0ff9728556ac112">TranslatorSwedish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a2aaf436d502e7ff77507c4aec6c97c21">TranslatorAfrikaans::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ac67a6cbd79d0f4798444774710268ac3">TranslatorBrazilian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#ae211def1cf4090d7c6ba95a17cee56a6">TranslatorCatalan::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#ab8a261818e6df7f81bd14f6d6df06946">TranslatorCzech::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#adba89d170b98628154fc322cd9b43b9f">TranslatorDanish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a17a3ecdea79819bfd85cebbba548c0f7">TranslatorDutch::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a96b2257e88d83669541b4ad1a90723ff">TranslatorEsperanto::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a95555a3814e4a86486a3aba260a93b37">TranslatorFinnish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a2663e4f67740b4eae7e9b73b98c13692">TranslatorFrench::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#a77c658fd5405269f4db1ec55306db57f">TranslatorHungarian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a48c8fdb51e1fcd333e9e56492ca0d6b2">TranslatorItalian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a3b7cbe63733177dec388a689b8182091">TranslatorLatvian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#a6fed8e83a0ce653ff010480a59c399f1">TranslatorLithuanian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#aacf529d31c701d6a72e7c66595690519">TranslatorNorwegian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#ab3674c0324b5bf20db8f2fe0ba4a6d8c">TranslatorPolish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a815cd8cc443f54b18d471e667f946ebe">TranslatorPortuguese::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#aecdec02bcee3133b75bfcf56ccbd233d">TranslatorRomanian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#a13ab2dea6837617150b27ccaf142a5e8">TranslatorSerbian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a81b8dd359e157846c4db7ae825f370c9">TranslatorSlovak::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#a50c84ef3244b3230186bd4a81d814a35">TranslatorSlovene::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a1e5df11140031c349dcf08058f81a9d5">TranslatorSpanish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#aaf7c0af00e79f06ee6770c861c88f5d1">TranslatorSwedish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a87e8230599f42efce2bbca2f35e31521">NamespaceDefImpl::updateLocalName</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a0332e2befe926de95b367c391a0ac70c">DotNode::writeDEF</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a4be56bbbeefd5d44b58d28f05c446725">DotNode::writeDocbook</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a84a2aa61638b8af08560219e2a5140f1">ConfigOption::writeStringList</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#aed2051e58bce93b9250b99108a77ae00">DotNode::writeXML</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>.
</div>
</div>

### prepend() {#a0a6a8fe99e596b149ee15138fa8dcf0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::prepend (const char * s)</td>
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


<p>Definition at line 407 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">407</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>(0,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a92e0ed943a60680559a637016d45b14f">MemberDefImpl::addListReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a7137defdca68d716cface04a9b9aa37e">addSTLClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1a03a99aa2c0df2c963f8c778d63cd0e">ClassDefImpl::addUsedByClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aac1c07c7768af4eeab0317c9531c13fb">ClassDefImpl::addUsedClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2ad951bc5df5d08796970a7271734b40">MemberDefImpl::anchor</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab36fc7f90b85f9a369604444f3a6e203">VHDLOutlineParser::createFlow</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac3000b9ef927fdbbdf460fcf5d1c712e">createOutputDirectory</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa28cb040180473ff3e2ef3e03e55cbcc">MemberDefImpl::fieldType</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af86247b60aae3c8229391fbece0cb1a7">generatePHPVariableLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a30e9e6fd4264e1d7dd92eb516c9feb6e">MemberDefImpl::getDeclType</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad3269d7d65675a5e83889f4a98f5610b">getExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aea75bbe69de2d8ff75d41a40df878894">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aa01a87c51143a53315d534acc1340693">FlowChart::getNodeName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aca6957f15c9d66857d63b1290bb0ce07">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="#af428b9307683dc2c090f7d837138b438">quoted</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a931044da5493c1d83ca77898996140c4">MemberDefImpl::setAnchor</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#a3d9eb667db4f11f9bd15cfc0b8fe45b4">setDotFontPath</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a065cc165c287399167d790bd59ac60e0">MemberDefImpl::sourceRefName</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#afe30a1c1a560e4a85206dc7623a17dc4">LatexDocVisitor::startDiaFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa197e546b10f737e78020b97fdf23cb9">LatexDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aeef2a244f24ea46106204e063fae5273">LatexDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a83690d197c135515366011602fa36f34">HtmlDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a3264ee5213c549e45cd13604e62e7719">HtmlDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#a41b0a17952879ed6de614c8bd4ff6c9f">LatexCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#ad7fd3e3cc19d62798aa65d318a42e47c">RTFCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a52015628829279296a6334d955676868">writeMemberReference</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a928ca1eefc8caee8adbf197d19f9d687">HtmlDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>.
</div>
</div>

### prepend() {#acffefc809c8b24e32df929c2985bdf48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::prepend (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 412 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acffefc809c8b24e32df929c2985bdf48">412</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#acffefc809c8b24e32df929c2985bdf48">prepend</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>(0,s.<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### prepend() {#a792b11db11f131e280229450e9ad4fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::prepend (const std::string &amp; s)</td>
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


<p>Definition at line 417 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a792b11db11f131e280229450e9ad4fba">417</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a792b11db11f131e280229450e9ad4fba">prepend</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>(0,s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### prepend() {#a8270e394feda059b463a3588a41d6e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::prepend (std::string_view s)</td>
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


<p>Definition at line 422 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8270e394feda059b463a3588a41d6e5e">422</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a8270e394feda059b463a3588a41d6e5e">prepend</a>( std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>(0,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### quoted() {#af428b9307683dc2c090f7d837138b438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::quoted ()</td>
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


<p>Definition at line 260 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af428b9307683dc2c090f7d837138b438">260</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#af428b9307683dc2c090f7d837138b438">quoted</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> start=0, sl=<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size(), <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=sl-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (start&lt;sl  &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[start])) start++; </span><span class="doxyHighlightComment">// skip over leading whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (start==sl) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(); </span><span class="doxyHighlightComment">// only whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;start &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]))   <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>--;   </span><span class="doxyHighlightComment">// skip over trailing whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsQuotes=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i]!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// stripped string has at least non-whitespace unquoted character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; !needsQuotes) </span><span class="doxyHighlightComment">// check if the to be quoted part has at least one whitespace character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">          needsQuotes = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i] ==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">          needsQuotes |= <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> result(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.substr(start,1+<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-start));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsQuotes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">        result.<a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">        result.<a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5ccdad61a2bd619961d1546602a03322">writeLatexMakefile</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ab02ed8a64b15dea3af44838d67a039a5">writeMakeBat</a>.
</div>
</div>

### rawData() {#a5f5c9dc172d638c8d7b07010d100117a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * QCString::rawData ()</td>
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
<p>Returns a writable pointer to the data.</p>

<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f5c9dc172d638c8d7b07010d100117a">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[0]; }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#ad396917a059d354b1ff240b9af3a006c">ResourceMgr::copyResourceAs</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.
</div>
</div>

### remove() {#a66f15f4dde9edaf0aac741fa7d57bae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::remove (size_t index, size_t len)</td>
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


<p>Definition at line 427 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66f15f4dde9edaf0aac741fa7d57bae8">427</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ol = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;ol &amp;&amp; len&gt;0) <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.erase(index,index+len&gt;=ol ? std::string::npos : len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad28f49b99078162fd63bd325db5c2b2b">VhdlDocGen::convertFileNameToClassName</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a411f4f042964d6e24c0376f1378da1a8">VhdlDocGen::parseForBinding</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4584e2262b81979f6d9b88c070c78753">VhdlDocGen::parseForConfig</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="#ab536413a2bab9fe536e82067a3f164ed">replace</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a67e22ceaa05ae493f2f3892681aec351">splitString</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a848aaabaf4d7b73351e6850d05254d99">stripKeyword</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>.
</div>
</div>

### removeWhiteSpace() {#ae5612f003ab58972eb5769811876c5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::removeWhiteSpace ()</td>
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
<p>returns a copy of this string with all whitespace removed</p>

<p>Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5612f003ab58972eb5769811876c5e3">286</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#ae5612f003ab58972eb5769811876c5e3">removeWhiteSpace</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sl==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string result = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> src=0,dst=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (src&lt;sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[src])) result[dst++]=<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[src];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">        src++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dst&lt;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size()) result.resize(dst);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>.
</div>
</div>

### repeat() {#a68253ebb5d12da7c53b5b9a748259b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::repeat (unsigned int n)</td>
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


<p>Definition at line 306 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68253ebb5d12da7c53b5b9a748259b9f">306</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a>(</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> result(n * <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>(), <a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (offset = 0; offset &lt; n * <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>(); offset += <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">        memcpy(result.<a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>() + offset, <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">ExplicitSize</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>, <a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a> and <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#a7f125260c31c05f6171796b108bf3835">LatexGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aca2825b298ae76954b78b95987572e98">LatexGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a5e6096c4c5fb47fb771afedea2f64384">LatexGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac8c5de108411c791b04d6501347fd614">LatexGenerator::startTitleHead</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#a29a3e4d6eb0dc0f67374c0fc6fbbe1b2">LatexGenerator::writeInheritedSectionTitle</a>.
</div>
</div>

### replace() {#ab536413a2bab9fe536e82067a3f164ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::replace (size_t index, size_t len, const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 434 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab536413a2bab9fe536e82067a3f164ed">212</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#ab536413a2bab9fe536e82067a3f164ed">QCString::replace</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>( index, len );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>( index, s );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad28f49b99078162fd63bd325db5c2b2b">VhdlDocGen::convertFileNameToClassName</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### reserve() {#a973167288278eae74d1d1c25313043fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QCString::reserve (size_t size)</td>
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
<p>Reserve space for <em>size</em> bytes without changing the string contents.</p>

<p>Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a973167288278eae74d1d1c25313043fe">172</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a973167288278eae74d1d1c25313043fe">reserve</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a> ) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.reserve(<a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>); }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad370f3cfa0f4a46e2afd73bd50de864b">docifyToString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3f2329035cfde039380d267efff68c76">removeEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.
</div>
</div>

### resize() {#a747c587f5fee7b891e52909aa309323e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QCString::resize (size_t newlen)</td>
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


<p>Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a747c587f5fee7b891e52909aa309323e">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a747c587f5fee7b891e52909aa309323e">resize</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> newlen) { <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.resize(newlen); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#abc3bead6f8cce482f4db02c92a770ab5">alignText</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a3a30de88958d15c2cf424f7efc5c6ef9">stripAnonymousMarkers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae81df9187a70102c6f47ca6c2c5012f4">stripTrailingWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.
</div>
</div>

### right() {#a8f4aa5417f6a834f28c7148a1fe262d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::right (size_t len)</td>
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


<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f4aa5417f6a834f28c7148a1fe262d5">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>( </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty()    ? <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">             len&lt;<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size() ? <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.substr(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size()-len,len)) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">             *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::&#95;writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aac61019f2270df6f5bfa4efed4760845">ClassDefImpl::addTypeConstraints</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/mangen-cpp/#af6acf966d7ed7500f4ab36fbdce70db0">buildFileName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7b984704d9d6ad6819140f993d6bce4e">checkExtension</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a20350e5803a50856a69419c6473dd5a1">MemberList::countEnumValues</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#aa0944a06a26c8f552be061cd5060baa1">DocInternalRef::DocInternalRef</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acfc81350dc516af20831bcb14d6788c2">getCanonicalTemplateSpec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad7fe83480a1c139afa09ab1183da5ca5">getParserForFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a710af507a150913251c3885189b77fb8">isConstraintFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a7910d0ac9f615f9ce451bd0c71d15da6">VHDLOutlineParser::oneLineComment</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae0c5a702c29f403e331441abfe289d5b">rightScopeMatch</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5935e8ddff8337f8a43689e2713c8067">ManGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3b3bee35d0b539f857173e0a14ecbf63">stripAnonymousNamespaceScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78d33655f54cd45e22070b58a6dce6b6">stripScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a15f807d04ca6a15d183d7c05396bae30">trimBaseClassScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#a1cb314bd0d605efa7019319e3da26870">DotNode::writeUrl</a>.
</div>
</div>

### setNum() {#a87d2bfa3fcbf407c32fab784df368b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (short n)</td>
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


<p>Definition at line 444 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87d2bfa3fcbf407c32fab784df368b2d">444</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(</span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a69491156cedaf02dc6443e685d158087">compileOptions</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#adca7a84ec7d9e70efe47d6e395be099f">compileOptions</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a4bb486e09bd72d913eaee12efabae171">compileOptions</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a81e09fc4923e15a55d0e269ddef08e5d">compileOptions</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ab89d76e38155d470797f5d7bcdc1b74c">compileOptions</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a6078df856ea98140e2210721d1175764">convertIndexWordToAnchor</a>, <a href="/web-doxygen/docs/api/classes/condparser/#ad4fcf0ce5b9644fb6ff130cf7e335730">CondParser::evalOperator</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2086de9221c9c0a17efc40915a054852">generateAnonymousAnchor</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#af9cb5d8af596e5b9eb054f0b3a5c7e67">generateIndentLabel</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ada253943236861987284e1b340603dbd">VHDLOutlineParser::getNameID</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aa01a87c51143a53315d534acc1340693">FlowChart::getNodeName</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7467e3f0f800ca5303ce1e6e473cdcfe">RTFDocVisitor::getStyle</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a37a4055f986c73a8de48cd5d19bdd2dc">CitationManager::latexBibFiles</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a5c3ca80a615fbf6119e6aec28e60506d">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a8e90c9de4676d5baf1fb570c0c0c0495">pathToNode</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a4149b6b3cb3e0246eb2e0d47de02538f">warn&#95;line</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a> and <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a76a75ed644eb3f75d36151f9d82f862f">yearToString</a>.
</div>
</div>

### setNum() {#a26b813d24e05da8782921d21abda996f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (uint16_t n)</td>
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


<p>Definition at line 450 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26b813d24e05da8782921d21abda996f">450</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a26b813d24e05da8782921d21abda996f">setNum</a>(uint16_t n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a985317d53986ff869f6200eba01da503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (int n)</td>
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


<p>Definition at line 456 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a985317d53986ff869f6200eba01da503">456</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a985317d53986ff869f6200eba01da503">setNum</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a12ba2a3c200768b4f3b062ea80c90a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (uint32_t n)</td>
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


<p>Definition at line 462 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12ba2a3c200768b4f3b062ea80c90a20">462</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a12ba2a3c200768b4f3b062ea80c90a20">setNum</a>(uint32_t n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a258a420449cd4af46dca39fc4d5966ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (long n)</td>
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


<p>Definition at line 468 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a258a420449cd4af46dca39fc4d5966ee">468</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a258a420449cd4af46dca39fc4d5966ee">setNum</a>(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a96f922d046d633efe346301f9f4a2e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (long long n)</td>
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


<p>Definition at line 474 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96f922d046d633efe346301f9f4a2e1d">474</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a96f922d046d633efe346301f9f4a2e1d">setNum</a>(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a91737ecae84142dc8f0b224e6e3ab6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (unsigned long long n)</td>
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


<p>Definition at line 480 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91737ecae84142dc8f0b224e6e3ab6b4">480</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a91737ecae84142dc8f0b224e6e3ab6b4">setNum</a>(</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### setNum() {#a9ce207a13873ddad6ceba4e7ed475736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::setNum (unsigned long n)</td>
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


<p>Definition at line 486 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ce207a13873ddad6ceba4e7ed475736">486</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#a9ce207a13873ddad6ceba4e7ed475736">setNum</a>(</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a> = std::to_string(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### simplifyWhiteSpace() {#a8d6ace0deb439b916b9f97f54a6c9cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::simplifyWhiteSpace ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>return a copy of this string with leading and trailing whitespace removed and multiple whitespace characters replaced by a single space</p>

<p>Declaration at line 303 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">185</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a8d6ace0deb439b916b9f97f54a6c9cc2">QCString::simplifyWhiteSpace</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() )                            </span><span class="doxyHighlightComment">// nothing to do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> result( <a href="#a16362990092a086b505e08f102df4dff">length</a>(), <a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">ExplicitSize</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *from  = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *to    = result.<a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *first = to;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( *from &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*from) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">      from++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( *from &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*from) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      *to++ = *from++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *from )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      *to++ = 0x20;                       </span><span class="doxyHighlightComment">// ' '</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( to &gt; first &amp;&amp; *(to-1) == 32 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    to--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  *to = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  result.<a href="#a747c587f5fee7b891e52909aa309323e">resize</a>( </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(to - result.<a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">ExplicitSize</a>, <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>, <a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>, <a href="#a747c587f5fee7b891e52909aa309323e">resize</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::&#95;docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a87fd251583954635281c516ceee7fd34">findAndRemoveWord</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a6e965e20450faf656e93988e7d2b0219">MemberDefImpl::setBitfields</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a>.
</div>
</div>

### size() {#a957be37e3b98707fc7e8daeff18e391b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t QCString::size ()</td>
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
<p>Returns the length of the string, not counting the 0-terminator.</p>

<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a957be37e3b98707fc7e8daeff18e391b">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size(); }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/structs/vhdloutlineparser/private/#a09e1a5b366fadb1761f46049e67df6c5">VHDLOutlineParser::Private::parseVhdlfile</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="#acc813fb23f557904aa94f100b37958d3">QCString</a>, <a href="#a68253ebb5d12da7c53b5b9a748259b9f">repeat</a>, <a href="#a973167288278eae74d1d1c25313043fe">reserve</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a848aaabaf4d7b73351e6850d05254d99">stripKeyword</a>.
</div>
</div>

### sprintf() {#aa2dccf89cb25346c3ee81d75aa5859da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; QCString::sprintf (const char * format, ...)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 186 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2dccf89cb25346c3ee81d75aa5859da">29</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *format, ... )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  va_list ap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  va_start( ap, format );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> minlen=256;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = <a href="#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&lt;minlen) { <a href="#a747c587f5fee7b891e52909aa309323e">resize</a>(minlen+1); l=minlen; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n=vsnprintf( <a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>(), l+1, format, ap);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n&lt;0) n=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a747c587f5fee7b891e52909aa309323e">resize</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  va_end( ap );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>, <a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a> and <a href="#a747c587f5fee7b891e52909aa309323e">resize</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad7328f0606e5f8d93daecd7d5babee1d">addFormula</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a2996b202ffa4a28fb842837caae8fa0f">dateToRTFDateString</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab828dbdc362a011d3f909e34033b5642">escapeComment</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a226824f63e34c286eebdac9da5bdc61b">escapeName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a8e905b506e051ad396d13f2c9d1a075b">escapeObject</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a33327842933290b16d8001c0e13e3ffe">escapeWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a62cf6f788807da125c5433670c59d393">generateFormula</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#ae3d49e892872b87e8c5d19fc190b6512">DotGfxHierarchyTable::getBaseName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#aa2872f3c154bf7c3cfa319bcf83e3fac">includeTagFileAttributes</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a10998c967b5e151acf3dad299deb0bc9">FormulaManager::initFromRepository</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#ad1beec9fe5f9860bd405a3b6b4ac4780">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aef9d8a33c82dbef016b68d619f0b2856">saveObjCContext</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/lexcode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/sqlcode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/xmlcode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aba3b3876764867eeb32b9dcce3d4b63b">LayoutParser::startNavEntry</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/translatorarmenian/#acd43e1b822275305d9a5354416cc30fd">TranslatorArmenian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a8248217f537c77268d1234e6ae35eddf">TranslatorBrazilian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorbulgarian/#a841844631a96d11a77b207ac95422c61">TranslatorBulgarian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#ad60659ff434761daabc56f9f77977db5">TranslatorCatalan::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorchinese/#ab1cffedb58d7be72593e127a44073e82">TranslatorChinese::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorchinesetraditional/#a5367a1c5581e94b3c04c01fffbf09079">TranslatorChinesetraditional::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#abb674c5c915e2639ec90d999fdb06052">TranslatorCroatian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#a48dbb0987ef8a609d957e77d34fecf79">TranslatorCzech::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#ac40e0892349d42a9fabb31303167144b">TranslatorDanish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a46362ae980c39d207331da4230b7df6f">TranslatorDutch::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorenglish/#aa6991d0552441c113a6cf77141fbca1c">TranslatorEnglish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a2d1863bd4a81fba0bdc2f64da64cff13">TranslatorEsperanto::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a0489b420bf5cefb382a60e0ed9b321c3">TranslatorFrench::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorgerman/#a87858d6448c071d356d95fbed8d47ff3">TranslatorGerman::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorgreek/#a94037402002f402e0ccb0c678266cd10">TranslatorGreek::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorhindi/#aa6a3cf8f88a7140f67269c605d1517d8">TranslatorHindi::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#ae497d7a1dced82f6429f510f9100c7b6">TranslatorHungarian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorindonesian/#a1a91510cb3f785a431a2524ca0a2e4b7">TranslatorIndonesian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a7b7966171ce79f576be8633bdf6b023b">TranslatorItalian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#a8d47e6b08a1e0891e2d888368c5486e5">TranslatorJapanese::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorkorean/#aefdb7f778ca4a2cb0ad2b56f7da75f2e">TranslatorKorean::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#aadc3da45979c3604d045e6e9869e65b3">TranslatorLatvian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a304888be07c676b30efd318f7104e930">TranslatorPersian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#ab29b0dd4101a0083192ca98fc4833f87">TranslatorPolish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a9e66883bfd3e53d274bbc43fc5b1120a">TranslatorPortuguese::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#a0afdc34ae68acf0fa9fdb2c7d25751a7">TranslatorRomanian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorrussian/#ae6c921f7c81dfa9ce77ad418f034e1f0">TranslatorRussian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#af614b84f1ff42f5d670ec3218f4f5055">TranslatorSlovak::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a21998c1f90649235df06dadc5f647d17">TranslatorSpanish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#a0be2bc338c029e0dff6da160350d2c3d">TranslatorSwedish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorturkish/#a1571c7455d3f62872bbd0facb74c6670">TranslatorTurkish::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorukrainian/#aac68ca486d31dcbba89de6c2e4d793ca">TranslatorUkrainian::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#abf1c2318a734ffb00d9d128e83cd0e7e">TranslatorJapanese::trWriteList</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#aeb01acd1ef9dbeb87e35e7eae24143b1">DotNode::writeArrow</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a3f65f51eefb97cf188587b56115d973a">DotNode::writeBox</a>, <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#ae8e105816d60cf56b75c2d13f9d85048">writeJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ae3e188b81cd05fbb4e12621850e7d5e4">DocbookCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#a41b0a17952879ed6de614c8bd4ff6c9f">LatexCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#ad7fd3e3cc19d62798aa65d318a42e47c">RTFCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a53279dc86a635990c995e61bc3b7104c">DocbookGenerator::writePageLink</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>.
</div>
</div>

### startsWith() {#a1f43c0a4958cf17f086dc0e3a4b13a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::startsWith (const char * s)</td>
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


<p>Definition at line 492 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f43c0a4958cf17f086dc0e3a4b13a68">492</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty() || s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.rfind(s,0)==0; </span><span class="doxyHighlightComment">// looking "backward" starting and ending at index 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac04b30f86754dceee0e3019c7dd99b9f">MemberDefImpl::&#95;isAnonymousBitField</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::&#95;writeEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#abe42707109ca3bbad6ad388f766d8218">DocHtmlCell::alignment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1e3ec8fc9a7cd41405fc0c2039b07b57">copyStyleSheet</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a582f332d778bad3d6e991a75a2448d06">MemberDefImpl::createTemplateInstanceMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ca04f9cfa633f92d16cdab66a3635db">handleImage</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a8d3ac23f544142e96ccf645831743432">AnchorGenerator::looksGenerated</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a6185cb6e624208c3f4ffc97ac506b992">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa50164ebc8d5c581d278e1d0f7f2ca54">removeLongPathMarker</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a544c6fd0814756e0e4ab69eac035ff7f">startsWithKeyword</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a301116112cb06af3d6fa71fdb8c9b940">stripTrailingReturn</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.
</div>
</div>

### startsWith() {#acd585269e99db0640d91e8179152bb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::startsWith (const std::string &amp; s)</td>
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


<p>Definition at line 498 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd585269e99db0640d91e8179152bb34">498</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acd585269e99db0640d91e8179152bb34">startsWith</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.rfind(s,0)==0; </span><span class="doxyHighlightComment">// looking "backward" starting and ending at index 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.
</div>
</div>

### startsWith() {#a856bdc110760824279f35a6f6f9a67a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::startsWith (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line 503 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a856bdc110760824279f35a6f6f9a67a9">503</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;s )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty() || s.<a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.<a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.rfind(s.<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>(),0)==0; </span><span class="doxyHighlightComment">// looking "backward" starting and ending at index 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>.
</div>
</div>

### str() {#a875e9ad762554ef12f3ed69b015bb245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; QCString::str ()</td>
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


<p>Definition at line 537 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a875e9ad762554ef12f3ed69b015bb245">537</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::&#95;setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::&#95;writeReimplementedBy</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#a32a09a931c866f27807ceeabb48946f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#ab0ee1991e602ebd106de0fe5884979b6">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#acaf21f8a88dc994cf1de14246e679579">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::add</a>, <a href="/web-doxygen/docs/api/classes/symbolmap/#a5ee5036f5adbd147a02e4aa476fc8b72">SymbolMap&lt; T &gt;::add</a>, <a href="/web-doxygen/docs/api/structs/constraintclassdef/#aa0de42a40a226e9f3373d90386d9d271">ConstraintClassDef::addAccessor</a>, <a href="/web-doxygen/docs/api/structs/usesclassdef/#ac3b5c2f408116e9da744697d8d876796">UsesClassDef::addAccessor</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#a1dd9ba2dc2586e4dcd08ea7da6d93b69">Crawlmap::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a207d66f561747d53a0df54a5019cc45b">addDefine</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">ModuleDefImpl::addExportedModule</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad7328f0606e5f8d93daecd7d5babee1d">addFormula</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a01a6226c4a4e8c587a78af168e5e3938">HtmlHelp::addImageFile</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#acabf04c9722d33c1b5240a56ad93d572">ModuleDefImpl::addImport</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aae7040ab38171d6666f314331a4d6335">FileDefImpl::addIncludedByDependency</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#af6e40a9b55ddf54aebef42114a99a861">FileDefImpl::addIncludeDependency</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#aafc27f940e1c9768a97427452dd1f86b">Crawlmap::addIndexFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a06d4ceaf4d108051a76d49986f56b8a0">HtmlHelp::addIndexFile</a>, <a href="/web-doxygen/docs/api/classes/crawlmap/#af14459516bd2c63e2637f45b668fd676">Crawlmap::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a70d9d3885e2b3e6a8587e6c59e02afa0">HtmlHelpIndex::addItem</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ad36e56c8bfd19605777cd5511cd13cbb">addLocalVar</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a081e6f14489f0d6aaa301b077bd58dff">ModuleDefImpl::addPartition</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#adfc55933ed845c9b089f305b365d8e6b">Preprocessor::addSearchDir</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a199dcaa1d5e5095d5ab54059c720395e">DefinitionImpl::addSourceReferencedBy</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afeac94f61e5f5fcc1d604b23eb78b140">DefinitionImpl::addSourceReferences</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#ac6c55156ed17cff5a6cb350df9182d06">HtmlHelp::addStyleSheetFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a9f3ce7c21549a8e70e535371ef94aaaf">addUsingDirective</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/classes/variablecontext/#a8ecf50e05c0af1f854d21a2d0574dbcf">VariableContext::addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ab657e2797fb2f8d57ca202215fc2003d">FlowChart::alignCommentNode</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afe5f7e6498fa0fb5d155c4c0a86e46de">buildListOfUsingDecls</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a685b08b025bb0139299eb40a0704df31">buildVarList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">DocParser::checkRetvalName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#ab09e45c115a5beefe878b915613bd3a3">checkVhdlString</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a268cc4c891922e026401a55c6aa0f0e2">DocbookGenerator::cleanup</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bec825c1c10f337c697e790f6cac8d6">HtmlGenerator::cleanup</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a07848c2f5582d593414b92cddc749172">LatexGenerator::cleanup</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a35f00a2ffcb843a96a9eec65cc1d9eee">ManGenerator::cleanup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae64f5253a619794433e3e2689360b1f2">RTFGenerator::cleanup</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acf309728fac71ec225044c1afe6ae9f7">computeVerifiedDotPath</a>, <a href="#ab2617e8fdb6c52fb762a52f7252d61ed">contains</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4a4f83dcfb4d9490aaf82e597940b27c">containsWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5b6b9f769803f3b7fb05ee88eb8c4c71">copyIcon</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6e5984219541c97536c13b07baadb83f">copyLogo</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1e3ec8fc9a7cd41405fc0c2039b07b57">copyStyleSheet</a>, <a href="/web-doxygen/docs/api/classes/dotmanager/#a250e1025f4793941521d21081df9511f">DotManager::createFilePatcher</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#ab24723d7cedd2c780f895fea971fb484">FormulaManager::createFormulasTexFile</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a2634e192e6fb1db99bb22fb62a9e8c0f">createJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a7e2356fcdbce7babc9b65ba24be66fc9">ModuleManager::createModuleDef</a>, <a href="/web-doxygen/docs/api/classes/translator/#a087f8254bcdad1c3a79183abb76d0033">Translator::createNoun</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac3000b9ef927fdbbdf460fcf5d1c712e">createOutputDirectory</a>, <a href="/web-doxygen/docs/api/classes/dotmanager/#affaee30a9c348252f29053e3dc53c77f">DotManager::createRunner</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#a6150feb21a667df3826df38c1a0878fa">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#a5fad70772de2ff561c5883f5a8919c5d">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::del</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#aad65fb794eac705b1f9e896602c59bbe">deliverablesPresent</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a21e0a716a4ba27ef05394fdd16276eec">determineInkscapeVersion</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a027224fbb504c5436845bb85a7c511a0">DotCallGraph::DotCallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration::DotGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph::DotInclDepGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a3e01aed32d5dbf43b922e4152b65b54f">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::endElement</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a06a8a71d6e6d9f8e93cee750e2faa0ef">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::endEnumValue</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a>, <a href="/web-doxygen/docs/api/classes/condparser/#a6eacc43d99d9d65ba89361b9846b0c6f">CondParser::evalVariable</a>, <a href="/web-doxygen/docs/api/files/src/portable-cpp/#a1a05b42d6baa2f85ed112c8a7c67ac01">ExistsOnPath</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a32503e1a48b7258fa8879ac99f6ece1a">DefinitionImpl::externalReference</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a337616be3bea43c6c1a7c898bdbfda7c">extractClassNameFromType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0a8ffacc302979f9f812ab6608967287">extractDirection</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a2904843bbc4e5d707386d5dce049692e">CitationManager::find</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#aa43fff2a2b489b77245b73478b391136">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#a3d3f8cefe5cfd6d46e95889817b92140">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="#a5381d8547e101adef3ee87f8d54c9925">find</a>, <a href="#a7227fa9c8db91de17b12305d5a6ca984">find</a>, <a href="/web-doxygen/docs/api/classes/sectionrefs/#a5cce204b4a51a49e478243581d36b1e2">SectionRefs::find</a>, <a href="/web-doxygen/docs/api/classes/symbolmap/#a84904cdc40a6daca784500b454fbc813">SymbolMap&lt; T &gt;::find</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a87fd251583954635281c516ceee7fd34">findAndRemoveWord</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab13551a402d45747996978c41713af58">VhdlDocGen::findArchitecture</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae13abaf328534f92b57bb6af8208f31d">findBaseClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3946c5d60512e109396ca6ae867f48ae">findClassEntries</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a103513ad1b948e1fc70ba3a98c761e31">findFilePath</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="#ab6cbf7f8b8943606766d6e3d2e26fc70">findRev</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/variablecontext/#aa4cfe2b318b52c33b4e28b5840275d85">VariableContext::findVariable</a>, <a href="/web-doxygen/docs/api/structs/fmt/formatter-fa4158f88247518f118826f72729e28e/#aad86e9af7bc315cbd52e7ee1245e22b4">fmt::formatter&lt; QCString &gt;::format</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a39444ed87f324cf10eca40dca31c8bf9">generateDEF</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a62cf6f788807da125c5433670c59d393">generateFormula</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#aef1d730d619e5441ab6206a8fd5b1a45">FormulaManager::generateImages</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0ab63cb2f20e16fa82b9b687d2b4b00">genericPatternMatch</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">ConfigImpl::get</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a2bc16163bd7e09f324093b641113b077">ResourceMgr::get</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#a5730ddb0e69085c4031028a2eb383f14">FilterCache::getFileContentsDisk</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#ad313a32a960f39f775ebb6d5bc8c5fe1">FilterCache::getFileContentsPipe</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae1c14782849e08d5ef42d9ae8290c18b">VhdlDocGen::getIndexWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa243c32e58b19c8d831a826a03bf3562">getMscImageMapFromFile</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a80b6d2e3602cbd740b728267e66ba355">ModuleManager::getPrimaryInterface</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">getResolvedNamespace</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7467e3f0f800ca5303ce1e6e473cdcfe">RTFDocVisitor::getStyle</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ebe50fa5f3c75360a5fcfda16fd0317">handleFileInfoResult</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ac85a1b3f99ceba03bd7be38caa0b7600">ManGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a10998c967b5e151acf3dad299deb0bc9">FormulaManager::initFromRepository</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>, <a href="/web-doxygen/docs/api/files/src/trace-cpp/#a94476ca22ba9fc237ecdad6bf2a4c5e8">initTracing</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#acbc101ba2926c6324a479b572ff3c377">CitationManager::insert</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab17d77238a46be34e30fc71ed51db35a">insertDimension</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aca89c5ef98d812439cd931a762b49213">keyWordsFortranC</a>, <a href="/web-doxygen/docs/api/files/src/debug-cpp/#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a37a4055f986c73a8de48cd5d19bdd2dc">CitationManager::latexBibFiles</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a36e764c0a931ef05c53d3695489d198e">loadExtensions</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a1a60858edb01bcbd780025cecdf65c8f">loadStylesheet</a>, <a href="/web-doxygen/docs/api/classes/mapper/#aa80abfd581280947c7a3c5849b589465">Mapper&lt; T &gt;::map</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">HtmlEntityMapper::name2sym</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac13e6fab478750b5fc094a78e8fcb149">openDbConnection</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c6662051d765cb0a355382ab05c14a1">openOutputFile</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ae5703d567f3b2538d3832276940fd734">operator!=</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af32530eae2ce36e648a925f28f1ca781">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41c844f5b9078d32e11a14b45b6f5c2d">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a611ec420e06726e8061f4fe83c3f8a6f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac219ce4773970158e118d1d3b57ebd78">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ad3bf496cd5400f4d0149b5e4a627735c">operator+</a>, <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a4f1fac62cd55edb5dcfc30b7fe24c48d">operator&lt;&lt;</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a6d31c2fb52c60b7f411f3b687fdb2840">TextStream::operator&lt;&lt;</a>, <a href="#afa8d791236dd93fd013f718a91bf6bbd">operator=</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ad13e4c478edbecac20fcbce2b86f1c35">operator==</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a3ac956f197291fa939c052de93bd3d16">outputString</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a411f4f042964d6e24c0376f1378da1a8">VhdlDocGen::parseForBinding</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4584e2262b81979f6d9b88c070c78753">VhdlDocGen::parseForConfig</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#a1f76d619b8096fc4446808b378b8ce14">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#a98b0589fd4091da2efa1c5ee2da43f73">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::prepend</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a772414bc571e725007f1c8bc15ebb355">preProcessFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a2286f03edc20befca29cd2b2f57de1f6">QCString</a>, <a href="#abeb844f296f351124bfe2e83b7c54976">QCString</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfb0efa72e3e5ed08b1881ccd8332e5e">readFileOrDirectory</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/files/src/codefragment-cpp/#a8c33a344ab42361aefb90541f2be4e6e">readTextFileByName</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#a150d4d51073cb46cdf38a236cc120d0a">ParserManager::registerExtension</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#a434a1a473c7c10ebe1929d41d0af6690">ParserManager::registerParser</a>, <a href="/web-doxygen/docs/api/classes/symbolmap/#a36b000d1d74ec4820b0d1c3a57dd645c">SymbolMap&lt; T &gt;::remove</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#af2aa6035c4917cd2d139f59850c5a008">resetPDFSize</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a8e6aba48ce1a2e82d0401f666a45c1d3">resolveTypeBoundProcedures</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9f4db29aeeb7d0f2ab033f6235a69912">RTFGenerator::rtf&#95;BList&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afd3768dca041d56a01b01061bb41aec5">RTFGenerator::rtf&#95;CList&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a5b9f9d4a335e0e68bad617fdceb9e318">RTFCodeGenerator::rtf&#95;Code&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9f8483e6f7e65c06e5f4f507f0887f67">RTFGenerator::rtf&#95;DList&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7527ce8866206a633c1cfb684cc22574">RTFGenerator::rtf&#95;EList&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac5b5b70aa6da3566aa9724b3aa617192">RTFGenerator::rtf&#95;LCList&#95;DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#abd244447df22d110ad410b69c357fdf3">Portable::setenv</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#a11addfe71baa15d57b1423b4aab53f76">FilterCache::shrinkBuffer</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a1b616091b56e2ca65f7966157c4a1493">splitSearchTokens</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a487b3d40047a75c0612f66ab78f61d96">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::startElement</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a143683b28b248b9cf805d5de8291dafc">RTFCodeGenerator::startFontClass</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a84c295f784c9b8da3706ee857ba2c70d">substitute</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ac2e29048cffc72c3bed439cff5b02cd4">Portable::unsetenv</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afb6a683a89f794ddafb8f8fd1cb55fc9">DefinitionImpl::writeDocAnchorsToTagFile</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a2885c2afac4a6401e64d765eb44f2d0e">FlowChart::writeEdge</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a47c5aeaf257c00ebecc958a4c78c5de9">DotGfxHierarchyTable::writeGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ae7a5c86a2927e880a7c8413e57275811">DotNode::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl/#aeebc63bda55bc226c43f72d75e1e92a4">TextGeneratorSqlite3Impl::writeLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a> and <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a>.
</div>
</div>

### stripLeadingAndTrailingEmptyLines() {#a6444196e54d0b736cef5c9edd8c262d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::stripLeadingAndTrailingEmptyLines ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 256 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 573 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6444196e54d0b736cef5c9edd8c262d9">573</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a6444196e54d0b736cef5c9edd8c262d9">QCString::stripLeadingAndTrailingEmptyLines</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> start=0,p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip leading empty lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=s[p]) &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s[p]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">      start=++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip trailing empty lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">  p=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&gt;=start &amp;&amp; s.at(p)==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) p--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&gt;=start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=s[p]) &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) p--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s[p]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=p+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    p--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("stripLeadingAndTrailingEmptyLines(%d-%d)\n",start,end);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.substr(start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.
</div>
</div>

### stripPrefix() {#af363dfe85e56f873aa3a373c70a33b24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::stripPrefix (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix)</td>
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


<p>Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af363dfe85e56f873aa3a373c70a33b24">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.isEmpty() || <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.rfind(<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.data(),0)==0) </span><span class="doxyHighlightComment">// string starts with prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.erase(0,<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/scanner-l/#a424adbb16d98e3ef52a4229263c68aca">addKnRArgInfo</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aae48ed44191778c99e285f17b7e14377">VHDLOutlineParser::addLibUseClause</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a2ddaa20cd52c580374e791c2b1ff1286">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a0cf2ae6bf35f920987bb1804a5fed8b7">generateMemLink</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a30e9e6fd4264e1d7dd92eb516c9feb6e">MemberDefImpl::getDeclType</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad52018c3c0f56dc9cfdfad34b45fae26">VHDLOutlineParser::handleFlowComment</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7cb019e5059fa4aa866434f8c310c210">inlineTemplateArgListToDoc</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="#a3524dfec9219699243b6baf0f33bd0f1">stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### stripPrefix() {#a3524dfec9219699243b6baf0f33bd0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool QCString::stripPrefix (const char * prefix)</td>
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


<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3524dfec9219699243b6baf0f33bd0f1">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3524dfec9219699243b6baf0f33bd0f1">stripPrefix</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(<a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>.
</div>
</div>

### stripWhiteSpace() {#a66269a694d9e6961bfd145bb4ca72f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::stripWhiteSpace ()</td>
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
<p>returns a copy of this string with leading and trailing whitespace removed</p>

<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66269a694d9e6961bfd145bb4ca72f42">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl = <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sl==0 || (!<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[0]) &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[sl-1]))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> start=0,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=sl-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (start&lt;sl &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[start])) start++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (start==sl) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(); </span><span class="doxyHighlightComment">// only whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;start &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>])) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>.substr(start,1+<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-start));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>, <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::&#95;setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::&#95;writeEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3e6c42b51465b9d08e7e894fe3673b5b">FileDefImpl::acquireFileVersion</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a207d66f561747d53a0df54a5019cc45b">addDefine</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad7328f0606e5f8d93daecd7d5babee1d">addFormula</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a424adbb16d98e3ef52a4229263c68aca">addKnRArgInfo</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aac61019f2270df6f5bfa4efed4760845">ClassDefImpl::addTypeConstraints</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a38b6783aaabbed92ec114e917385f739">appStringLower</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbba640854380aad154effc800d8b63d">buildPageList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac191ad1786e980d514c4535505cf99d6">checkFileName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ac853f7c85a98e5ef7040604706c7b80c">compareString</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a06a8a71d6e6d9f8e93cee750e2faa0ef">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::endEnumValue</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ac494d47958d1f5413e97e355624ca8db">extractBind</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9f3bbbf9ecc3d8cf038de3a62cb6cb5">extractCanonicalArgType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa92d2aaaadff51d927a9629cdad82a9">extractNoExcept</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9807194e65b4cbe485854d383aabdb21">findMainPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acfc81350dc516af20831bcb14d6788c2">getCanonicalTemplateSpec</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ebe50fa5f3c75360a5fcfda16fd0317">handleFileInfoResult</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad52018c3c0f56dc9cfdfad34b45fae26">VHDLOutlineParser::handleFlowComment</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a048c00592e372edb8bd1cd16389b57a9">handleGuard</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ca04f9cfa633f92d16cdab66a3635db">handleImage</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac6f2811c13f5afdc6966f8985ff9908c">handleInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7cb019e5059fa4aa866434f8c310c210">inlineTemplateArgListToDoc</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a07ca80df8cb26c1c11d0cb22e326b01d">CitationManager::insertCrossReferencesForBibFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a01336ef49f88d4dd7f574c3db13ad774">isCastKeyword</a>, <a href="/web-doxygen/docs/api/classes/configlist/#a9a4272c2073dc3d52cd5738401e1eee4">ConfigList::isDefault</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa41ca3cde0467d35291f6d6a48be0c44">ClassDefImpl::isExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>, <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aefb4ef8e7f1dd80f48ceee263197a572">FlowChart::printPlantUmlNode</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad9be6018763c3edcf6ef39be40d2fb9e">projectLogoSize</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#ada088a153d3ab756e5be8bd628b10e9a">splitKnRArg</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa39c36a133f69ff84e4d617e3915f9c8">startOfRequiresExpression</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a301116112cb06af3d6fa71fdb8c9b940">stripTrailingReturn</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a>.
</div>
</div>

### toInt() {#a100a41fa6ba318b8b2ace175cd20f1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int QCString::toInt (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 438 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a100a41fa6ba318b8b2ace175cd20f1eb">249</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a100a41fa6ba318b8b2ace175cd20f1eb">QCString::toInt</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>( ok, base ));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab17d77238a46be34e30fc71ed51db35a">insertDimension</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e8f1fbd720c602f867aa536e450462">runQHelpGenerator</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#ae879a7a89bcbc71d0d30a83791b8498d">TranslatorSlovak::trAndMore</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
</div>
</div>

### toLong() {#aa4a9dec36c09c8c131a0e5e9bb71d98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">long QCString::toLong (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 440 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 260 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">260</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">QCString::toLong</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> val=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> max_mult = INT_MAX / base;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> neg = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !p )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                   </span><span class="doxyHighlightComment">// skip leading space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( l &amp;&amp; *p == </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    neg = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p == </span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight"> ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// NOTE: toULong() code is similar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l || !<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dv = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; *p&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight"> ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      dv = *p-</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p &gt;= </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; *p &lt;= </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( val &gt; max_mult || (val == max_mult &amp;&amp; dv &gt; (INT_MAX%base)+neg) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    val = base*val + dv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( neg )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    val = -val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                   </span><span class="doxyHighlightComment">// skip trailing space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">    is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">bye:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ok )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    *ok = is_ok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> is_ok ? val : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok&#95;in&#95;base</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a> and <a href="#afcfb73b0f862461d60da84504fa4d4cd">toShort</a>.
</div>
</div>

### toShort() {#afcfb73b0f862461d60da84504fa4d4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">short QCString::toShort (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 436 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 229 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcfb73b0f862461d60da84504fa4d4cd">229</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> <a href="#afcfb73b0f862461d60da84504fa4d4cd">QCString::toShort</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> v = <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>( ok, base );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ok &amp;&amp; *ok &amp;&amp; (v &lt; -32768 || v &gt; 32767) ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">    *ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    v = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(v);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#aa4a9dec36c09c8c131a0e5e9bb71d98e">toLong</a>.
</div>
</div>

### toUInt() {#ab43def7ec8f0cdca5bf722f952e0cf19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t QCString::toUInt (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 439 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab43def7ec8f0cdca5bf722f952e0cf19">254</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint32_t <a href="#ab43def7ec8f0cdca5bf722f952e0cf19">QCString::toUInt</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>( ok, base ));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>.
</div>
</div>

### toUInt64() {#a524e1cd9e1c24e91d57b1cb91513fa67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t QCString::toUInt64 (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 442 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 356 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a524e1cd9e1c24e91d57b1cb91513fa67">356</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint64_t <a href="#a524e1cd9e1c24e91d57b1cb91513fa67">QCString::toUInt64</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  uint64_t val=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint64_t max_mult = 1844674407370955161ULL;  </span><span class="doxyHighlightComment">// ULLONG_MAX/10, rounded down</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !p )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                      </span><span class="doxyHighlightComment">// skip leading space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p == </span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// NOTE: toULong() code is similar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l || !<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t dv = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; *p&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight"> ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      dv = *p-</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p &gt;= </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; *p &lt;= </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( val &gt; max_mult || (val == max_mult &amp;&amp; dv &gt; (ULLONG_MAX%base)) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">    val = base*val + dv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                   </span><span class="doxyHighlightComment">// skip trailing space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">bye:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ok )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    *ok = is_ok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> is_ok ? val : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok&#95;in&#95;base</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>.
</div>
</div>

### toULong() {#a592f86f3d758cb9285967c195f2f1824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned long QCString::toULong (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 441 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 312 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a592f86f3d758cb9285967c195f2f1824">312</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> <a href="#a592f86f3d758cb9285967c195f2f1824">QCString::toULong</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> val=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> max_mult = 429496729;             </span><span class="doxyHighlightComment">// UINT_MAX/10, rounded down</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !p )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                   </span><span class="doxyHighlightComment">// skip leading space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p == </span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// NOTE: toLong() code is similar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l || !<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok_in_base</a>(*p,base) ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t dv = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; *p&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight"> ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">      dv = *p-</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( *p &gt;= </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; *p &lt;= </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">        dv = *p - </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( val &gt; max_mult || (val == max_mult &amp;&amp; dv &gt; (UINT_MAX%base)) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> bye;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">    val = base*val + dv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( l &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(*p) )                   </span><span class="doxyHighlightComment">// skip trailing space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">    l--,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !l )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">    is_ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">bye:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ok )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    *ok = is_ok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> is_ok ? val : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a1835b22d1d4e6579094726089a6832ad">ok&#95;in&#95;base</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ab43def7ec8f0cdca5bf722f952e0cf19">toUInt</a> and <a href="#a8d31136b4f5f614640bd277d49182135">toUShort</a>.
</div>
</div>

### toUShort() {#a8d31136b4f5f614640bd277d49182135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t QCString::toUShort (bool * ok=nullptr, int base=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 437 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d31136b4f5f614640bd277d49182135">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint16_t <a href="#a8d31136b4f5f614640bd277d49182135">QCString::toUShort</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *ok,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> base)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> v = <a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>( ok, base );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ok &amp;&amp; *ok &amp;&amp; (v &gt; 65535) ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    *ok = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    v = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint16_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(v);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a592f86f3d758cb9285967c195f2f1824">toULong</a>.
</div>
</div>

### upper() {#a113ff6fe5b14585eebdcafbf2fe88cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString QCString::upper ()</td>
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


<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a113ff6fe5b14585eebdcafbf2fe88cc4">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a> <a href="#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>(<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>(<a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a2027564d4381eb6e539320ee8b2e0bcd">convertUTF8ToUpper</a>, <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a> and <a href="#ad691e1087cc03e14e00d1147ae0ecab7">QCString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a8fd031de6dc372d115ffd400a079fd19">TranslatorAfrikaans::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ab920c6c849cbe6ca181cb7efe4d1d8ef">TranslatorBrazilian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#abeb7cee64d567513c5b6244cf4a431ec">TranslatorCatalan::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#a09a17e262f3b2e90b2c55605f6dc5219">TranslatorCzech::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#a977499d4c707fb5913baf8871869e96a">TranslatorDanish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a587d06a96240ff6a61ed1b8a33658f3a">TranslatorDutch::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a90f6875eb086e11dc144f69690bee9f4">TranslatorEsperanto::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a205d35db17367515b7aca6d451885e5d">TranslatorFinnish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#ae226daa02d58dd042ca5f77a90f222e5">TranslatorFrench::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#aef452b564046eb574852739e89d8eb43">TranslatorHungarian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a3341f96ed21e91bd45ca5fd1314f4dd0">TranslatorItalian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a2569649d9fe65ec604548acdb0f6226a">TranslatorLatvian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#a1ee6c826869f34abbcdc132ecb44f849">TranslatorLithuanian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#accac5d3afb97530bb7039ffab1af0f87">TranslatorNorwegian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#a03f0a4b1a2cc89f81e524bd38dffd836">TranslatorPolish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a5d2bc6da7ecde60b9b361e27ba2175da">TranslatorPortuguese::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#a3cb0de7566c1f2ed6699d4ac4de373f4">TranslatorRomanian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#aeac9ab8b6a97959e4885fb2c65ae7bdb">TranslatorSerbian::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a2f3e0c4664e0608a5060d24b13d0a61c">TranslatorSlovak::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#a97f9768906b403c9c74a7a693bac7a30">TranslatorSlovene::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a4d9965d2a03082b81ffe81f6c99d02e3">TranslatorSpanish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorswedish/#a48da7d6eb2bde4dca0ff9728556ac112">TranslatorSwedish::trDayOfWeek</a>, <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a2aaf436d502e7ff77507c4aec6c97c21">TranslatorAfrikaans::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ac67a6cbd79d0f4798444774710268ac3">TranslatorBrazilian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#ae211def1cf4090d7c6ba95a17cee56a6">TranslatorCatalan::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorczech/#ab8a261818e6df7f81bd14f6d6df06946">TranslatorCzech::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#adba89d170b98628154fc322cd9b43b9f">TranslatorDanish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatordutch/#a17a3ecdea79819bfd85cebbba548c0f7">TranslatorDutch::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a96b2257e88d83669541b4ad1a90723ff">TranslatorEsperanto::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a95555a3814e4a86486a3aba260a93b37">TranslatorFinnish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorfrench/#a2663e4f67740b4eae7e9b73b98c13692">TranslatorFrench::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#a77c658fd5405269f4db1ec55306db57f">TranslatorHungarian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatoritalian/#a48c8fdb51e1fcd333e9e56492ca0d6b2">TranslatorItalian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a3b7cbe63733177dec388a689b8182091">TranslatorLatvian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#a6fed8e83a0ce653ff010480a59c399f1">TranslatorLithuanian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#aacf529d31c701d6a72e7c66595690519">TranslatorNorwegian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorpolish/#ab3674c0324b5bf20db8f2fe0ba4a6d8c">TranslatorPolish::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a815cd8cc443f54b18d471e667f946ebe">TranslatorPortuguese::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#aecdec02bcee3133b75bfcf56ccbd233d">TranslatorRomanian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#a13ab2dea6837617150b27ccaf142a5e8">TranslatorSerbian::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorslovak/#a81b8dd359e157846c4db7ae825f370c9">TranslatorSlovak::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorslovene/#a50c84ef3244b3230186bd4a81d814a35">TranslatorSlovene::trMonth</a>, <a href="/web-doxygen/docs/api/classes/translatorspanish/#a1e5df11140031c349dcf08058f81a9d5">TranslatorSpanish::trMonth</a> and <a href="/web-doxygen/docs/api/classes/translatorswedish/#aaf7c0af00e79f06ee6770c861c88f5d1">TranslatorSwedish::trMonth</a>.
</div>
</div>

### view() {#ac853c00269498870dfefa8185f2ee79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view QCString::view ()</td>
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


<p>Definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac853c00269498870dfefa8185f2ee79a">161</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string_view <a href="#ac853c00269498870dfefa8185f2ee79a">view</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>; }</span></span></div>

</div>


Reference <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m&#95;rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;rep {#a78d8b13c82f4e98372f8f5a2332ef40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string QCString::m_rep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 600 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78d8b13c82f4e98372f8f5a2332ef40a">600</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a78d8b13c82f4e98372f8f5a2332ef40a">m_rep</a>;</span></span></div>

</div>


Referenced by <a href="#a8f0a381fdae1427b1182baf0abde21e7">append</a>, <a href="#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>, <a href="#acb462b152dd61c53ccde9b7194c167a8">at</a>, <a href="#af4848e7058516bdbbcff3b43779aea30">clear</a>, <a href="#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>, <a href="#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>, <a href="#a320d19fe1ec83dedf40139c185c02157">endsWith</a>, <a href="#a6e46356724349472724ef65339235f21">endsWith</a>, <a href="#a08003d3e6c9acc46e4d392612ba492f7">fill</a>, <a href="#a0acc09ca029c0a255063a7dc610be340">insert</a>, <a href="#ae4e7678c93bacb8b7806597a8520ca54">insert</a>, <a href="#afc8c31db7525ff4aab929f6526675689">insert</a>, <a href="#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>, <a href="#aecf8b66312c4e97333219cc344c11a4f">left</a>, <a href="#a16362990092a086b505e08f102df4dff">length</a>, <a href="#a33688239622e659cfb469fbd62c9cccb">lower</a>, <a href="#a27136caf9c0bc4daca574cda6f113551">mid</a>, <a href="#a844a24565e79b45a3c0951e314408dc9">operator+=</a>, <a href="#a3f8a3c4ff3e86b352ac49ee366dc2c5c">operator+=</a>, <a href="#a39cc26ea20a11b2ef1bf77f1a8385606">operator+=</a>, <a href="#a62d42ad9cb74319f635c13328cb3eca8">operator+=</a>, <a href="#afa8d791236dd93fd013f718a91bf6bbd">operator=</a>, <a href="#a28b2434c36272cc772fd0d3a09109652">operator=</a>, <a href="#a52597e3bc7b763938231deb3a62a0dab">operator=</a>, <a href="#a1a72c5f97b350b7d062bc2f823ebad82">operator=</a>, <a href="#aa1c280e74c6e56e739447a5908eeaeab">operator&#91;&#93;</a>, <a href="#a565bc3e539ab20e33769c6ca429e180d">operator&#91;&#93;</a>, <a href="#a2286f03edc20befca29cd2b2f57de1f6">QCString</a>, <a href="#abeb844f296f351124bfe2e83b7c54976">QCString</a>, <a href="#a22e2da9d06bc6993d8a9daad3ff1699c">QCString</a>, <a href="#af7ecaca28abc410c18dc111da84a080c">QCString</a>, <a href="#acc813fb23f557904aa94f100b37958d3">QCString</a>, <a href="#a6e9d63203013767d7875ffe534899316">QCString</a>, <a href="#a0cd8dcd2de4abf36864f6f0c241f428a">QCString</a>, <a href="#af428b9307683dc2c090f7d837138b438">quoted</a>, <a href="#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>, <a href="#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>, <a href="#ae5612f003ab58972eb5769811876c5e3">removeWhiteSpace</a>, <a href="#a973167288278eae74d1d1c25313043fe">reserve</a>, <a href="#a747c587f5fee7b891e52909aa309323e">resize</a>, <a href="#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>, <a href="#a985317d53986ff869f6200eba01da503">setNum</a>, <a href="#a96f922d046d633efe346301f9f4a2e1d">setNum</a>, <a href="#a258a420449cd4af46dca39fc4d5966ee">setNum</a>, <a href="#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>, <a href="#a26b813d24e05da8782921d21abda996f">setNum</a>, <a href="#a12ba2a3c200768b4f3b062ea80c90a20">setNum</a>, <a href="#a91737ecae84142dc8f0b224e6e3ab6b4">setNum</a>, <a href="#a9ce207a13873ddad6ceba4e7ed475736">setNum</a>, <a href="#a957be37e3b98707fc7e8daeff18e391b">size</a>, <a href="#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>, <a href="#a856bdc110760824279f35a6f6f9a67a9">startsWith</a>, <a href="#acd585269e99db0640d91e8179152bb34">startsWith</a>, <a href="#a875e9ad762554ef12f3ed69b015bb245">str</a>, <a href="#a6444196e54d0b736cef5c9edd8c262d9">stripLeadingAndTrailingEmptyLines</a>, <a href="#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>, <a href="#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>, <a href="#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a> and <a href="#ac853c00269498870dfefa8185f2ee79a">view</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
