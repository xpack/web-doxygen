---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/textstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextStream` Class Reference

<p>Text streaming class that buffers data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TextStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/textstream-h">src/textstream.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> (size_t capacity=INITIAL_CAPACITY)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an empty stream object. <a href="#ae33c7c2cef250c2e773c7eccae7c7243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22b5c028814c2e880c258caff567184">TextStream</a> (std::ostream *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a text stream object for writing to a std::ostream. <a href="#aa22b5c028814c2e880c258caff567184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4167493d760a72984d1de542d12a9a">TextStream</a> (const std::string &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a text stream, initializing the buffer with string <em>s</em>. <a href="#a6c4167493d760a72984d1de542d12a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4cd037475e8c6f85c2665fe16b7dfb">~TextStream</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes any data that is buffered to the attached std::ostream. <a href="#aca4cd037475e8c6f85c2665fe16b7dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">operator&lt;&lt;</a> (char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a character to the stream. <a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6ef86e4ce8c8d1d2081352965f4018">operator&lt;&lt;</a> (unsigned char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an unsigned character to the stream. <a href="#aee6ef86e4ce8c8d1d2081352965f4018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161c4ba7441ee81fc558817211cce4bc">operator&lt;&lt;</a> (unsigned char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an unsigned character string to the stream. <a href="#a161c4ba7441ee81fc558817211cce4bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829e95bba078b91236e2df3ba3b61162">operator&lt;&lt;</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a C-style string to the stream. <a href="#a829e95bba078b91236e2df3ba3b61162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d31c2fb52c60b7f411f3b687fdb2840">operator&lt;&lt;</a> (const QCString &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> to the stream. <a href="#a6d31c2fb52c60b7f411f3b687fdb2840">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25252516016426ddbb04481e4c40a798">operator&lt;&lt;</a> (const std::string &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a std::string to the stream. <a href="#a25252516016426ddbb04481e4c40a798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766bcb2fcaf9fc615131e66a5fce2717">operator&lt;&lt;</a> (signed short i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a signed short integer to the stream. <a href="#a766bcb2fcaf9fc615131e66a5fce2717">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">operator&lt;&lt;</a> (unsigned short i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a unsigned short integer to the stream. <a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efd56716095f7c011ce6f5981446af9">operator&lt;&lt;</a> (signed int i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a signed integer to the stream. <a href="#a4efd56716095f7c011ce6f5981446af9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6fc03e6de6c855495af00f6f9b09a1">operator&lt;&lt;</a> (unsigned int i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a unsigned integer to the stream. <a href="#afe6fc03e6de6c855495af00f6f9b09a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69bdd4e0a8262e78b9e624a359f05b7a">operator&lt;&lt;</a> (T i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a size_t integer to the stream. <a href="#a69bdd4e0a8262e78b9e624a359f05b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7107b1c22e3ec8488216d91aaeeeab">operator&lt;&lt;</a> (float f)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a float to the stream. <a href="#a2b7107b1c22e3ec8488216d91aaeeeab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">operator&lt;&lt;</a> (double d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a double to the stream. <a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a> (std::ostream *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets or changes the std::ostream to write to. <a href="#a18a4ee87242fc2b8e31941a71e622fd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af285dfbd0040f7be9f3704738db024de">setFile</a> (FILE *f)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::ostream *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d61011a2d8962b0bdbec11483ae5790">stream</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the attached std::ostream object. <a href="#a1d61011a2d8962b0bdbec11483ae5790">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74762855a83645704bbe8b79c53c614">file</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa78941b7f04d95ca3be7d11073828f0">write</a> (const char *buf, size_t len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a array of character to the stream. <a href="#aaa78941b7f04d95ca3be7d11073828f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907937b613a56aa4124608b3a092b820">flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushes the buffer. <a href="#a907937b613a56aa4124608b3a092b820">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc87f49c9d496ce6409dd4e49226e11d">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears any buffered data. <a href="#afc87f49c9d496ce6409dd4e49226e11d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8457da22d874f4eb30b35ffe87ebd0">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the contents of the buffer as a std::string object. <a href="#aca8457da22d874f4eb30b35ffe87ebd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c42948b189c9d16fe5eb9ae12112e74">str</a> (const std::string &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the buffer's contents to string <em>s</em>. <a href="#a6c42948b189c9d16fe5eb9ae12112e74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31970b450c75ccca13f56940853010e">str</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the buffer's contents to string <em>s</em> Any data already in the buffer will be flushed. <a href="#ad31970b450c75ccca13f56940853010e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the buffer is empty. <a href="#a0859a9bfd6a7b6bafc7050d9f3aef046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> (uint32_t n, bool neg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a string representation of an integer to the buffer. <a href="#a42463de0e3fa4777714f8e8fc4f9355c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a> (double d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::ostream *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2cc389f03492be4163601478f0d9118">m_s</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> = nullptr</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a> = 4096</td>
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

<p>Text streaming class that buffers data.</p>


<p>Simpler version of std::ostringstream that has much better performance.</p>


<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextStream() {#ae33c7c2cef250c2e773c7eccae7c7243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream::TextStream (size_t capacity=<a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a>)</td>
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

<p>Creates an empty stream object.</p>

<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> capacity = <a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.reserve(capacity);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a> and <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">operator&lt;&lt;</a>, <a href="#a829e95bba078b91236e2df3ba3b61162">operator&lt;&lt;</a>, <a href="#a6d31c2fb52c60b7f411f3b687fdb2840">operator&lt;&lt;</a>, <a href="#a25252516016426ddbb04481e4c40a798">operator&lt;&lt;</a>, <a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">operator&lt;&lt;</a>, <a href="#a2b7107b1c22e3ec8488216d91aaeeeab">operator&lt;&lt;</a>, <a href="#a4efd56716095f7c011ce6f5981446af9">operator&lt;&lt;</a>, <a href="#a766bcb2fcaf9fc615131e66a5fce2717">operator&lt;&lt;</a>, <a href="#a69bdd4e0a8262e78b9e624a359f05b7a">operator&lt;&lt;</a>, <a href="#a161c4ba7441ee81fc558817211cce4bc">operator&lt;&lt;</a>, <a href="#aee6ef86e4ce8c8d1d2081352965f4018">operator&lt;&lt;</a>, <a href="#afe6fc03e6de6c855495af00f6f9b09a1">operator&lt;&lt;</a> and <a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">operator&lt;&lt;</a>.</p>

</div>
</div>

### TextStream() {#aa22b5c028814c2e880c258caff567184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream::TextStream (std::ostream * s)</td>
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

<p>Create a text stream object for writing to a std::ostream.</p>



:::info
<p>data is buffered until <a href="#a907937b613a56aa4124608b3a092b820">flush()</a> is called or the object is destroyed.</p>
:::


<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa22b5c028814c2e880c258caff567184">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#aa22b5c028814c2e880c258caff567184">TextStream</a>(std::ostream *s) : <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.reserve(<a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a>, <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>.</p>

</div>
</div>

### TextStream() {#a6c4167493d760a72984d1de542d12a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream::TextStream (const std::string &amp; s)</td>
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

<p>Create a text stream, initializing the buffer with string <em>s</em>.</p>

<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c4167493d760a72984d1de542d12a9a">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a6c4167493d760a72984d1de542d12a9a">TextStream</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s) : <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.reserve(s.length()+<a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a> and <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TextStream() {#aca4cd037475e8c6f85c2665fe16b7dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream::~TextStream ()</td>
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

<p>Writes any data that is buffered to the attached std::ostream.</p>

<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca4cd037475e8c6f85c2665fe16b7dfb">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#aca4cd037475e8c6f85c2665fe16b7dfb">~TextStream</a>() { <a href="#a907937b613a56aa4124608b3a092b820">flush</a>(); }</span></span></div>

</div>


<p>Reference <a href="#a907937b613a56aa4124608b3a092b820">flush</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;&lt;() {#af72300a280a492b7e0bd4fcd9fb7b7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (char c)</td>
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

<p>Adds a character to the stream.</p>

<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#aee6ef86e4ce8c8d1d2081352965f4018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (unsigned char c)</td>
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

<p>Adds an unsigned character to the stream.</p>

<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee6ef86e4ce8c8d1d2081352965f4018">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#aee6ef86e4ce8c8d1d2081352965f4018">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a161c4ba7441ee81fc558817211cce4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (unsigned char * s)</td>
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

<p>Adds an unsigned character string to the stream.</p>

<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a161c4ba7441ee81fc558817211cce4bc">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a161c4ba7441ee81fc558817211cce4bc">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">(*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=*p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">          p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a829e95bba078b91236e2df3ba3b61162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (const char * s)</td>
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

<p>Adds a C-style string to the stream.</p>

<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a829e95bba078b91236e2df3ba3b61162">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a829e95bba078b91236e2df3ba3b61162">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s) <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a6d31c2fb52c60b7f411f3b687fdb2840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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

<p>Adds a <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> to the stream.</p>

<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d31c2fb52c60b7f411f3b687fdb2840">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a6d31c2fb52c60b7f411f3b687fdb2840">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a25252516016426ddbb04481e4c40a798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (const std::string &amp; s)</td>
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

<p>Adds a std::string to the stream.</p>

<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25252516016426ddbb04481e4c40a798">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a25252516016426ddbb04481e4c40a798">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a766bcb2fcaf9fc615131e66a5fce2717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (signed short i)</td>
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

<p>Adds a signed short integer to the stream.</p>

<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a766bcb2fcaf9fc615131e66a5fce2717">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a766bcb2fcaf9fc615131e66a5fce2717">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">signed</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>(i,i&lt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a2c5bb0c9e5ebab3bef398d1e3ae3026b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (unsigned short i)</td>
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

<p>Adds a unsigned short integer to the stream.</p>

<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>(i,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a4efd56716095f7c011ce6f5981446af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (signed int i)</td>
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

<p>Adds a signed integer to the stream.</p>

<p>Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4efd56716095f7c011ce6f5981446af9">158</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a4efd56716095f7c011ce6f5981446af9">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">signed</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>(i,i&lt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#afe6fc03e6de6c855495af00f6f9b09a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (unsigned int i)</td>
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

<p>Adds a unsigned integer to the stream.</p>

<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe6fc03e6de6c855495af00f6f9b09a1">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#afe6fc03e6de6c855495af00f6f9b09a1">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>(i,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a69bdd4e0a8262e78b9e624a359f05b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename std::enable_if&lt; std::is_same&lt; T, size_t &gt;::value, T &gt;::type * = nullptr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (T i)</td>
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

<p>Adds a size_t integer to the stream.</p>


<p>We use SFINAE to avoid a compiler error in case size_t already matches the 'unsigned int' overload.</p>


<p>Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a69bdd4e0a8262e78b9e624a359f05b7a">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a69bdd4e0a8262e78b9e624a359f05b7a">operator&lt;&lt;</a>( T i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a2b7107b1c22e3ec8488216d91aaeeeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (float f)</td>
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

<p>Adds a float to the stream.</p>

<p>Definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b7107b1c22e3ec8488216d91aaeeeab">184</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a2b7107b1c22e3ec8488216d91aaeeeab">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a>(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(f));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a59a3771bfe8030d4a2a2a4ac8d6aa13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; TextStream::operator&lt;&lt; (double d)</td>
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

<p>Adds a double to the stream.</p>

<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> &amp;<a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">operator&lt;&lt;</a>( </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a> and <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#afc87f49c9d496ce6409dd4e49226e11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::clear ()</td>
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

<p>Clears any buffered data.</p>

<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc87f49c9d496ce6409dd4e49226e11d">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc87f49c9d496ce6409dd4e49226e11d">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>

</div>
</div>

### empty() {#a0859a9bfd6a7b6bafc7050d9f3aef046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TextStream::empty ()</td>
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

<p>Returns true iff the buffer is empty.</p>

<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0859a9bfd6a7b6bafc7050d9f3aef046">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>.</p>

</div>
</div>

### file() {#ab74762855a83645704bbe8b79c53c614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE * TextStream::file ()</td>
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



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab74762855a83645704bbe8b79c53c614">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    FILE *<a href="#ab74762855a83645704bbe8b79c53c614">file</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a>.</p>

</div>
</div>

### flush() {#a907937b613a56aa4124608b3a092b820}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::flush ()</td>
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

<p>Flushes the buffer.</p>


<p>If a std::ostream is attached, the buffer's contents will be written to the stream.</p>


<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a907937b613a56aa4124608b3a092b820">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a907937b613a56aa4124608b3a092b820">flush</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>-&gt;write(<a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.c_str(),<a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">        fwrite(<a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.c_str(),1,<a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.length(),<a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>, <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> and <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/qhp/#ad187b30da8187b859054c6271108b660">Qhp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="#af285dfbd0040f7be9f3704738db024de">setFile</a>, <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>, <a href="#ad31970b450c75ccca13f56940853010e">str</a>, <a href="#a6c42948b189c9d16fe5eb9ae12112e74">str</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a66989e6892ad6bbb539241dedbfc4f9e">FlowChart::writeFlowChart</a> and <a href="#aca4cd037475e8c6f85c2665fe16b7dfb">~TextStream</a>.</p>

</div>
</div>

### setFile() {#af285dfbd0040f7be9f3704738db024de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::setFile (FILE * f)</td>
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



<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af285dfbd0040f7be9f3704738db024de">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af285dfbd0040f7be9f3704738db024de">setFile</a>(FILE *f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> = f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a907937b613a56aa4124608b3a092b820">flush</a>, <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> and <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>.</p>

</div>
</div>

### setStream() {#a18a4ee87242fc2b8e31941a71e622fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::setStream (std::ostream * s)</td>
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

<p>Sets or changes the std::ostream to write to.</p>



:::info
<p>Any data already buffered will be flushed.</p>
:::


<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18a4ee87242fc2b8e31941a71e622fd2">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    void <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>(std::ostream *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a> = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a907937b613a56aa4124608b3a092b820">flush</a>, <a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a>, <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a> and <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/qhp/#ad187b30da8187b859054c6271108b660">Qhp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a> and <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>.</p>

</div>
</div>

### str() {#aca8457da22d874f4eb30b35ffe87ebd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string TextStream::str ()</td>
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

<p>Return the contents of the buffer as a std::string object.</p>

<p>Definition at line 229 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca8457da22d874f4eb30b35ffe87ebd0">229</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#aca8457da22d874f4eb30b35ffe87ebd0">str</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a8cb59745acc5f950c7fb14f28f4bfded">DotDirDeps::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a75c5c04dae25cb36a4715d0c49a4b196">DotGfxHierarchyTable::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a33f8dac0366f837a5880dc420d7c914d">DotGroupCollaboration::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotlegendgraph/#af02bfaa220696e0722080995d191d001">DotLegendGraph::computeTheGraph</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5261de94ef3b325400ae7b7a0f71630a">convertToLaTeX</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/entry/#a98c62e07d86951008cc8a0d60632c262">Entry::Entry</a>, <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#ae8dd6bba2e9ad92dab454422a3136a26">generateHtmlOutput</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa243c32e58b19c8d831a826a03bf3562">getMscImageMapFromFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a37bf597b522fe84aefa564de5b8489c2">latexEscapePDFString</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#aae9827c2942482734d1355ecddd0fa6d">templateSpec</a>, <a href="/web-doxygen/docs/api/structs/searchterm/#aec66f0d2f6bb7fb2905bc14546af792b">SearchTerm::termEncoded</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.</p>

</div>
</div>

### str() {#a6c42948b189c9d16fe5eb9ae12112e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::str (const std::string &amp; s)</td>
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

<p>Sets the buffer's contents to string <em>s</em>.</p>


<p>Any data already in the buffer will be flushed.</p>


<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c42948b189c9d16fe5eb9ae12112e74">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c42948b189c9d16fe5eb9ae12112e74">str</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a907937b613a56aa4124608b3a092b820">flush</a> and <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>

</div>
</div>

### str() {#ad31970b450c75ccca13f56940853010e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::str (const char * s)</td>
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

<p>Sets the buffer's contents to string <em>s</em> Any data already in the buffer will be flushed.</p>

<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad31970b450c75ccca13f56940853010e">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad31970b450c75ccca13f56940853010e">str</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s) <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a907937b613a56aa4124608b3a092b820">flush</a> and <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>

</div>
</div>

### stream() {#a1d61011a2d8962b0bdbec11483ae5790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::ostream * TextStream::stream ()</td>
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

<p>Returns the attached std::ostream object.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream()</a></p></dd>
</dl>


<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d61011a2d8962b0bdbec11483ae5790">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::ostream *<a href="#a1d61011a2d8962b0bdbec11483ae5790">stream</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#aa2cc389f03492be4163601478f0d9118">m_s</a>.</p>

</div>
</div>

### write() {#aaa78941b7f04d95ca3be7d11073828f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::write (const char * buf, size_t len)</td>
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

<p>Adds a array of character to the stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">buf</td>
<td class="doxyParamItemDescription"><p>the character buffer</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">len</td>
<td class="doxyParamItemDescription"><p>the number of characters in the buffer to write</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa78941b7f04d95ca3be7d11073828f0">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaa78941b7f04d95ca3be7d11073828f0">write</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.append(buf,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a> and <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### output\_double() {#a2626411e76cafb7b0cc97ad259f37615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::output_double (double d)</td>
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



<p>Definition at line 276 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2626411e76cafb7b0cc97ad259f37615">276</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a>( </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[64];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      snprintf(buf,64,</span><span class="doxyHighlightStringLiteral">"%f"</span><span class="doxyHighlight">,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=buf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="#a59a3771bfe8030d4a2a2a4ac8d6aa13a">operator&lt;&lt;</a> and <a href="#a2b7107b1c22e3ec8488216d91aaeeeab">operator&lt;&lt;</a>.</p>

</div>
</div>

### output\_int32() {#a42463de0e3fa4777714f8e8fc4f9355c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextStream::output_int32 (uint32_t n, bool neg)</td>
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

<p>Writes a string representation of an integer to the buffer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">n</td>
<td class="doxyParamItemDescription"><p>the absolute value of the integer</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">neg</td>
<td class="doxyParamItemDescription"><p>indicates if the integer is negative</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42463de0e3fa4777714f8e8fc4f9355c">263</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>( uint32_t n, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> neg )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[20];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = &amp;buf[19];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      *p = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( neg )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">        n = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(-</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">int32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(n));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">do</span><span class="doxyHighlight"> { *--p = (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(n%10)) + </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">; n /= 10; } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( n );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( neg ) *--p = </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>+=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>.</p>


<p>Referenced by <a href="#a4efd56716095f7c011ce6f5981446af9">operator&lt;&lt;</a>, <a href="#a766bcb2fcaf9fc615131e66a5fce2717">operator&lt;&lt;</a>, <a href="#a69bdd4e0a8262e78b9e624a359f05b7a">operator&lt;&lt;</a>, <a href="#afe6fc03e6de6c855495af00f6f9b09a1">operator&lt;&lt;</a> and <a href="#a2c5bb0c9e5ebab3bef398d1e3ae3026b">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_buffer {#a588661b14e0e238906c63ee414a232ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string TextStream::m_buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a588661b14e0e238906c63ee414a232ab">282</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a588661b14e0e238906c63ee414a232ab">m_buffer</a>;</span></span></div>

</div>


<p>Referenced by <a href="#afc87f49c9d496ce6409dd4e49226e11d">clear</a>, <a href="#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>, <a href="#a907937b613a56aa4124608b3a092b820">flush</a>, <a href="#af72300a280a492b7e0bd4fcd9fb7b7cd">operator&lt;&lt;</a>, <a href="#a829e95bba078b91236e2df3ba3b61162">operator&lt;&lt;</a>, <a href="#a6d31c2fb52c60b7f411f3b687fdb2840">operator&lt;&lt;</a>, <a href="#a25252516016426ddbb04481e4c40a798">operator&lt;&lt;</a>, <a href="#a161c4ba7441ee81fc558817211cce4bc">operator&lt;&lt;</a>, <a href="#aee6ef86e4ce8c8d1d2081352965f4018">operator&lt;&lt;</a>, <a href="#a2626411e76cafb7b0cc97ad259f37615">output_double</a>, <a href="#a42463de0e3fa4777714f8e8fc4f9355c">output_int32</a>, <a href="#aca8457da22d874f4eb30b35ffe87ebd0">str</a>, <a href="#ad31970b450c75ccca13f56940853010e">str</a>, <a href="#a6c42948b189c9d16fe5eb9ae12112e74">str</a>, <a href="#a6c4167493d760a72984d1de542d12a9a">TextStream</a>, <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a>, <a href="#aa22b5c028814c2e880c258caff567184">TextStream</a> and <a href="#aaa78941b7f04d95ca3be7d11073828f0">write</a>.</p>

</div>
</div>

### m\_f {#a88c5744dd7d51305aa75034481a9baab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE* TextStream::m_f = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88c5744dd7d51305aa75034481a9baab">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">    FILE *<a href="#a88c5744dd7d51305aa75034481a9baab">m_f</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ab74762855a83645704bbe8b79c53c614">file</a>, <a href="#a907937b613a56aa4124608b3a092b820">flush</a>, <a href="#af285dfbd0040f7be9f3704738db024de">setFile</a> and <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>.</p>

</div>
</div>

### m\_s {#aa2cc389f03492be4163601478f0d9118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::ostream* TextStream::m_s = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2cc389f03492be4163601478f0d9118">283</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::ostream *<a href="#aa2cc389f03492be4163601478f0d9118">m_s</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a907937b613a56aa4124608b3a092b820">flush</a>, <a href="#af285dfbd0040f7be9f3704738db024de">setFile</a>, <a href="#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>, <a href="#a1d61011a2d8962b0bdbec11483ae5790">stream</a> and <a href="#aa22b5c028814c2e880c258caff567184">TextStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### INITIAL\_CAPACITY {#aed326642b4edbab68d47dbd9c2f7901f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int TextStream::INITIAL_CAPACITY = 4096</td>
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



<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed326642b4edbab68d47dbd9c2f7901f">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aed326642b4edbab68d47dbd9c2f7901f">INITIAL_CAPACITY</a> = 4096;</span></span></div>

</div>


<p>Referenced by <a href="#a6c4167493d760a72984d1de542d12a9a">TextStream</a>, <a href="#ae33c7c2cef250c2e773c7eccae7c7243">TextStream</a> and <a href="#aa22b5c028814c2e880c258caff567184">TextStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
