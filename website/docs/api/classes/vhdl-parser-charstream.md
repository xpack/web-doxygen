---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/charstream
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CharStream` Class Reference

This class describes a character stream that maintains line and column number positions of the characters. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class vhdl::parser::CharStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">vhdlparser/CharStream.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a> (const JJChar *buf, int sz, int startline, int startcolumn, int buffersize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a> (const JJChar *buf, int sz, int startline, int startcolumn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac868943acf237740db51babde94cff7b">CharStream</a> (const JJString &amp;str, int startline, int startcolumn, int buffersize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a> (const JJString &amp;str, int startline, int startcolumn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a> (ReaderStream *input_stream, int startline, int startcolumn, int buffersize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> (ReaderStream *input_stream, int startline, int startcolumn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a> (ReaderStream *input_stream)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fb67513988560781f46bb5124f7966">~CharStream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9ca593901a797f6076230835b64b08">setTabSize</a> (int i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61bba1ec964d0ca48f36f71c7c465e3">getTabSize</a> (int i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba9c006a8d5510d8054df8dc83c4f063">getColumn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f578cd3509a81008518b7effdefda1">getLine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02054db796d1066becc894c70f429a3d">getEndColumn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac99aec0fdf89f82387c205f5e55e5a">getEndLine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0f2c3e5fa9250abf00696661639488">getBeginColumn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f296517fa30b9728af5ec8a9417800d">getBeginLine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34c97a27cde33d957e4f6eaabb025b1">getTrackLineColumn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12712c9866fb3495782fc0f28994d4d9">setTrackLineColumn</a> (bool val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea30b248a3b05857e3e60101afd2617a">backup</a> (int amount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Backs up the input stream by amount steps. <a href="#aea30b248a3b05857e3e60101afd2617a">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4550db4daa4e8ec748659002ddb2ad6c">BeginToken</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the next character that marks the beginning of the next token. <a href="#a4550db4daa4e8ec748659002ddb2ad6c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the next character from the selected input. <a href="#a9973e74a1dc5b4e1a99139b638286c42">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7244444767cc74b0c1fb507aee59dd7">ExpandBuff</a> (bool wrapAround)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18108809835cfda702105972cae6c9c7">FillBuff</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a string made up of characters from the marked token beginning to the current buffer position. <a href="#a4c4e17dcc7575e75150471e38531e7d2">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9deb0b2a4aa791d21620071e27c8e28b">GetSuffix</a> (int len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns an array of characters that make up the suffix of length 'len' for the currently matched token. <a href="#a9deb0b2a4aa791d21620071e27c8e28b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e7f3158e5d605c2391d7821d620b8d">DeleteBuffers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The lexer calls this function to indicate that it is done with the stream and hence implementations can free any resources held by this class. <a href="#aa3e7f3158e5d605c2391d7821d620b8d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a> (ReaderStream *input_stream, int startline, int startcolumn, int buffersize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c0e6b18d38b9df067c39ca157df86a">ReInit</a> (ReaderStream *input_stream, int startline, int startcolumn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147a1e6e2f7cc4d9dc423bc40a542a66">ReInit</a> (ReaderStream *input_stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb284dcfc5de4a898c89e7ba86ca188">ReInit</a> (const JJString &amp;str, int startline, int startcolumn, int buffersize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639909d8be82f388025752ddc28980cd">ReInit</a> (const JJString &amp;str, int startline, int startcolumn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8340206fb0e8eadbd9914fd833be6e0">adjustBeginLineColumn</a> (int newLine, int newCol)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ee195aafa845aefc1e9d6ec27fe85a">UpdateLineColumn</a> (JJChar c)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a> (int pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a> (int pos)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50828bf79317ddff0b210023624b99ff">column</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26311afec7fdd2e830f9021d93a07857">available</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a></td>
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

This class describes a character stream that maintains line and column number positions of the characters.


It also has the capability to backup the stream to some extent. An implementation of this class is used in the <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanager">TokenManager</a> implementation generated by JavaCCParser.

All the methods except backup can be implemented in any fashion. backup needs to be implemented correctly for the correct operation of the lexer. Rest of the methods are all used to get information like line number, column number and the string that constitutes a token and are not used by the lexer. Hence their implementation won't affect the generated lexer's operation.

Definition at line 31 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxySectionDef">

## Public Constructors

### CharStream() {#ac16b96fc00c5fe1c7587406d6869f9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> * buf, int sz, int startline, int startcolumn, int buffersize)</td>
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



Definition at line 166 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac16b96fc00c5fe1c7587406d6869f9b5">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> *buf, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sz, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> buffersize) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(<a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(buf, sz), startline, startcolumn, buffersize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#a242b0ade90665d38c5931af90a59038b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> * buf, int sz, int startline, int startcolumn)</td>
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



Definition at line 175 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a242b0ade90665d38c5931af90a59038b">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> *buf, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sz, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(<a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(buf, sz), startline, startcolumn, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#ac868943acf237740db51babde94cff7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; str, int startline, int startcolumn, int buffersize)</td>
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



Definition at line 183 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac868943acf237740db51babde94cff7b">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; str, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> buffersize) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(str, startline, startcolumn, buffersize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#a0582344d99aae18c75c7524f7b5a98b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; str, int startline, int startcolumn)</td>
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



Definition at line 192 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0582344d99aae18c75c7524f7b5a98b8">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; str, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(str, startline, startcolumn, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#a3da31e2203a8bcdf92b4726e83535104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream, int startline, int startcolumn, int buffersize)</td>
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



Definition at line 200 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3da31e2203a8bcdf92b4726e83535104">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>(<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *input_stream, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> buffersize) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(input_stream, startline, startcolumn, buffersize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#a7a3b115d9cb6f671539a8db6630f515c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream, int startline, int startcolumn)</td>
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



Definition at line 209 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a3b115d9cb6f671539a8db6630f515c">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>(<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *input_stream, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(input_stream, startline, startcolumn, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### CharStream() {#a82949d505a06f19999787ee61f85f7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::CharStream::CharStream (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream)</td>
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



Definition at line 217 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82949d505a06f19999787ee61f85f7a7">217</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>(<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *input_stream) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>(nullptr), <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>(nullptr), <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>(nullptr), <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>(0), <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>(0), </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>(0), <a href="#a50828bf79317ddff0b210023624b99ff">column</a>(0), <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>(0), <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>(false), <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>(false),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>(0), <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>(0), <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>(0), <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>(1), <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>(true),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>(nullptr), <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>(false) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(input_stream, 1, 1, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>, <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>, <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a50828bf79317ddff0b210023624b99ff">column</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>, <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>, <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>, <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>, <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>, <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CharStream() {#ab4fb67513988560781f46bb5124f7966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual vhdl::parser::CharStream::~CharStream ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 155 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4fb67513988560781f46bb5124f7966">155</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> <a href="#ab4fb67513988560781f46bb5124f7966">~CharStream</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa3e7f3158e5d605c2391d7821d620b8d">DeleteBuffers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#aa3e7f3158e5d605c2391d7821d620b8d">DeleteBuffers</a>, <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a> and <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustBeginLineColumn() {#af8340206fb0e8eadbd9914fd833be6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::adjustBeginLineColumn (int newLine, int newCol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 243 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

Reference <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a146a464d8664e6fe5cd764e866726ac1">newLine</a>.
</div>
</div>

### backup() {#aea30b248a3b05857e3e60101afd2617a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::backup (int amount)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Backs up the input stream by amount steps.


Lexer calls this method if it had already read some characters, but could not use them to match a (longer) token. So, they will be used again as the prefix of the next token and it is the implementation's responsibility to do this right.

Definition at line 69 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea30b248a3b05857e3e60101afd2617a">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea30b248a3b05857e3e60101afd2617a">backup</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> amount) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a> += amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> -= amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> &lt; 0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> += <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a> and <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>.
</div>
</div>

### BeginToken() {#a4550db4daa4e8ec748659002ddb2ad6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual JJChar vhdl::parser::CharStream::BeginToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the next character that marks the beginning of the next token.


All characters must remain in the buffer between two successive calls to this method to implement backup correctly.

Definition at line 82 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4550db4daa4e8ec748659002ddb2ad6c">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> <a href="#a4550db4daa4e8ec748659002ddb2ad6c">BeginToken</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> c = <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> = <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a> and <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>.
</div>
</div>

### DeleteBuffers() {#aa3e7f3158e5d605c2391d7821d620b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::DeleteBuffers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The lexer calls this function to indicate that it is done with the stream and hence implementations can free any resources held by this class.

Definition at line 153 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

Referenced by <a href="#ab4fb67513988560781f46bb5124f7966">\~CharStream</a>.
</div>
</div>

### endOfInput() {#a6a84b589f280fbac29dbb2325196bb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::CharStream::endOfInput ()</td>
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



Definition at line 162 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a84b589f280fbac29dbb2325196bb05">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a> == 0 &amp;&amp; <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> + 1 &gt;= <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a> &amp;&amp; <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>-&gt;endOfInput();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a> and <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>.
</div>
</div>

### ExpandBuff() {#ad7244444767cc74b0c1fb507aee59dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ExpandBuff (bool wrapAround)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 120 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.
</div>
</div>

### FillBuff() {#a18108809835cfda702105972cae6c9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::FillBuff ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 121 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

Referenced by <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### getBeginColumn() {#a3e0f2c3e5fa9250abf00696661639488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getBeginColumn ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e0f2c3e5fa9250abf00696661639488">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3e0f2c3e5fa9250abf00696661639488">getBeginColumn</a>()   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>(<a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>); }</span></span></div>

</div>


References <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a> and <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>.
</div>
</div>

### getBeginLine() {#a3f296517fa30b9728af5ec8a9417800d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getBeginLine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 58 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f296517fa30b9728af5ec8a9417800d">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3f296517fa30b9728af5ec8a9417800d">getBeginLine</a>()     { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>(<a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>); }</span></span></div>

</div>


References <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a> and <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>.
</div>
</div>

### getColumn() {#aba9c006a8d5510d8054df8dc83c4f063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getColumn ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 53 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba9c006a8d5510d8054df8dc83c4f063">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aba9c006a8d5510d8054df8dc83c4f063">getColumn</a>()        { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>(<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>); }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> and <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>.
</div>
</div>

### getEndColumn() {#a02054db796d1066becc894c70f429a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getEndColumn ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 55 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02054db796d1066becc894c70f429a3d">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a02054db796d1066becc894c70f429a3d">getEndColumn</a>()     { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>(<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>); }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> and <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>.
</div>
</div>

### getEndLine() {#abac99aec0fdf89f82387c205f5e55e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getEndLine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abac99aec0fdf89f82387c205f5e55e5a">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#abac99aec0fdf89f82387c205f5e55e5a">getEndLine</a>()       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>(<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>); }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> and <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>.
</div>
</div>

### GetImage() {#a4c4e17dcc7575e75150471e38531e7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual JJString vhdl::parser::CharStream::GetImage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns a string made up of characters from the marked token beginning to the current buffer position.


Implementations can return anything that they want to. For example, for efficiency, one might decide to just return NULL, which is a valid implementation.

Definition at line 129 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c4e17dcc7575e75150471e38531e7d2">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> <a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> &gt;= <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a> + <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> - <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a> + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a> + <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a> - <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>).append(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a> and <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>.
</div>
</div>

### getLine() {#a35f578cd3509a81008518b7effdefda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::CharStream::getLine ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 54 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35f578cd3509a81008518b7effdefda1">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a35f578cd3509a81008518b7effdefda1">getLine</a>()          { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>(<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>); }</span></span></div>

</div>


References <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> and <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>.
</div>
</div>

### GetSuffix() {#a9deb0b2a4aa791d21620071e27c8e28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual JJString vhdl::parser::CharStream::GetSuffix (int len)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns an array of characters that make up the suffix of length 'len' for the currently matched token.


This is used to build up the matched string for use in actions in the case of MORE. A simple and inefficient implementation of this is as follows :

Definition at line 142 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9deb0b2a4aa791d21620071e27c8e28b">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> <a href="#a9deb0b2a4aa791d21620071e27c8e28b">GetSuffix</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> + 1) &gt;= len) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a> + <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> - len + 1, len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a> + <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a> - (len - <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> - 1), len - <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> - 1).append(<a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> and <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>.
</div>
</div>

### getTabSize() {#ad61bba1ec964d0ca48f36f71c7c465e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::getTabSize (int i)</td>
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



Definition at line 34 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad61bba1ec964d0ca48f36f71c7c465e3">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">  <a href="#ad61bba1ec964d0ca48f36f71c7c465e3">getTabSize</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>; }</span></span></div>

</div>


Reference <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>.
</div>
</div>

### getTrackLineColumn() {#aa34c97a27cde33d957e4f6eaabb025b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool vhdl::parser::CharStream::getTrackLineColumn ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 60 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa34c97a27cde33d957e4f6eaabb025b1">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa34c97a27cde33d957e4f6eaabb025b1">getTrackLineColumn</a>()         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>; }</span></span></div>

</div>


Reference <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

### readChar() {#a9973e74a1dc5b4e1a99139b638286c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual JJChar vhdl::parser::CharStream::readChar ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the next character from the selected input.


The method of selecting the input is the responsibility of the class implementing this class.

Definition at line 95 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9973e74a1dc5b4e1a99139b638286c42">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a> &gt; 0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      --<a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      ++<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> == <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>[<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    ++<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a> &gt;= <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a18108809835cfda702105972cae6c9c7">FillBuff</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> c = <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>[<a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a01ee195aafa845aefc1e9d6ec27fe85a">UpdateLineColumn</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>, <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>, <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>, <a href="#a18108809835cfda702105972cae6c9c7">FillBuff</a>, <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>, <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>, <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a> and <a href="#a01ee195aafa845aefc1e9d6ec27fe85a">UpdateLineColumn</a>.

Referenced by <a href="#a4550db4daa4e8ec748659002ddb2ad6c">BeginToken</a>.
</div>
</div>

### ReInit() {#aab303980370a21a4540ddf6093fe5bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ReInit (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream, int startline, int startcolumn, int buffersize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 225 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a639909d8be82f388025752ddc28980cd">ReInit</a>, <a href="#a147a1e6e2f7cc4d9dc423bc40a542a66">ReInit</a> and <a href="#a93c0e6b18d38b9df067c39ca157df86a">ReInit</a>.
</div>
</div>

### ReInit() {#a93c0e6b18d38b9df067c39ca157df86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ReInit (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream, int startline, int startcolumn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 227 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93c0e6b18d38b9df067c39ca157df86a">227</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a93c0e6b18d38b9df067c39ca157df86a">ReInit</a>(<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *input_stream, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(input_stream, startline, startcolumn, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a> and <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>.
</div>
</div>

### ReInit() {#a147a1e6e2f7cc4d9dc423bc40a542a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ReInit (<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> * input_stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 231 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a147a1e6e2f7cc4d9dc423bc40a542a66">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a147a1e6e2f7cc4d9dc423bc40a542a66">ReInit</a>(<a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a> *input_stream) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(input_stream, 1, 1, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a> and <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>.
</div>
</div>

### ReInit() {#a8cb284dcfc5de4a898c89e7ba86ca188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ReInit (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; str, int startline, int startcolumn, int buffersize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 235 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.
</div>
</div>

### ReInit() {#a639909d8be82f388025752ddc28980cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::ReInit (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; str, int startline, int startcolumn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 238 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a639909d8be82f388025752ddc28980cd">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a639909d8be82f388025752ddc28980cd">ReInit</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; str, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startline,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startcolumn) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>(str, startline, startcolumn, <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL_BUFFER_SIZE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h/#a1d51567e0f6916e91f5bd3719d56cce6">INITIAL\_BUFFER\_SIZE</a> and <a href="#aab303980370a21a4540ddf6093fe5bf4">ReInit</a>.
</div>
</div>

### setTabSize() {#a3b9ca593901a797f6076230835b64b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void vhdl::parser::CharStream::setTabSize (int i)</td>
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



Definition at line 33 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b9ca593901a797f6076230835b64b08">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3b9ca593901a797f6076230835b64b08">setTabSize</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i) { <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a> = i; }</span></span></div>

</div>


Reference <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>.
</div>
</div>

### setTrackLineColumn() {#a12712c9866fb3495782fc0f28994d4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::setTrackLineColumn (bool val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 61 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12712c9866fb3495782fc0f28994d4d9">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a12712c9866fb3495782fc0f28994d4d9">setTrackLineColumn</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> val) { <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a> = val; }</span></span></div>

</div>


Reference <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### UpdateLineColumn() {#a01ee195aafa845aefc1e9d6ec27fe85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::CharStream::UpdateLineColumn (<a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 246 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

Referenced by <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getBufcolumn() {#a36665c2174fbfd9d427d35f2babbd818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::getBufcolumn (int pos)</td>
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



Definition at line 37 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36665c2174fbfd9d427d35f2babbd818">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a> &amp;&amp; pos&gt;=0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>[pos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.

Referenced by <a href="#a3e0f2c3e5fa9250abf00696661639488">getBeginColumn</a>, <a href="#aba9c006a8d5510d8054df8dc83c4f063">getColumn</a> and <a href="#a02054db796d1066becc894c70f429a3d">getEndColumn</a>.
</div>
</div>

### getBufline() {#aacc5ee96e0b1352acc4acde5a0e23aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::getBufline (int pos)</td>
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



Definition at line 44 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacc5ee96e0b1352acc4acde5a0e23aca">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a> &amp;&amp; pos&gt;=0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>[pos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a> and <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>.

Referenced by <a href="#a3f296517fa30b9728af5ec8a9417800d">getBeginLine</a>, <a href="#abac99aec0fdf89f82387c205f5e55e5a">getEndLine</a> and <a href="#a35f578cd3509a81008518b7effdefda1">getLine</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### available {#a26311afec7fdd2e830f9021d93a07857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::available</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 258 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26311afec7fdd2e830f9021d93a07857">258</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a26311afec7fdd2e830f9021d93a07857">available</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> and <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>.
</div>
</div>

### bufcolumn {#a3864d2bf9e3cfa405cab2026076cc3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int* vhdl::parser::CharStream::bufcolumn</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 249 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3864d2bf9e3cfa405cab2026076cc3ad">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">*               <a href="#a3864d2bf9e3cfa405cab2026076cc3ad">bufcolumn</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a> and <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>.
</div>
</div>

### buffer {#a9a130a9b60ebcf293d35f84cab89d8d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJChar* vhdl::parser::CharStream::buffer</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 250 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a130a9b60ebcf293d35f84cab89d8d1">250</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a>*                <a href="#a9a130a9b60ebcf293d35f84cab89d8d1">buffer</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a>, <a href="#a9deb0b2a4aa791d21620071e27c8e28b">GetSuffix</a> and <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### bufline {#a6b825e1a3515c2d88228264d624d0379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int* vhdl::parser::CharStream::bufline</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 248 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b825e1a3515c2d88228264d624d0379">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">*               <a href="#a6b825e1a3515c2d88228264d624d0379">bufline</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a> and <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>.
</div>
</div>

### bufpos {#aa2cbb8b449e060850a7de5632f30cc25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::bufpos</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 251 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2cbb8b449e060850a7de5632f30cc25">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#aa2cbb8b449e060850a7de5632f30cc25">bufpos</a>;</span></span></div>

</div>


Referenced by <a href="#aea30b248a3b05857e3e60101afd2617a">backup</a>, <a href="#a4550db4daa4e8ec748659002ddb2ad6c">BeginToken</a>, <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a>, <a href="#aba9c006a8d5510d8054df8dc83c4f063">getColumn</a>, <a href="#a02054db796d1066becc894c70f429a3d">getEndColumn</a>, <a href="#abac99aec0fdf89f82387c205f5e55e5a">getEndLine</a>, <a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a>, <a href="#a35f578cd3509a81008518b7effdefda1">getLine</a>, <a href="#a9deb0b2a4aa791d21620071e27c8e28b">GetSuffix</a> and <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### bufsize {#a10f6a94a722bf34e5618d41d6072dbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::bufsize</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 252 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10f6a94a722bf34e5618d41d6072dbee">252</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a10f6a94a722bf34e5618d41d6072dbee">bufsize</a>;</span></span></div>

</div>


Referenced by <a href="#aea30b248a3b05857e3e60101afd2617a">backup</a>, <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a>, <a href="#a9deb0b2a4aa791d21620071e27c8e28b">GetSuffix</a> and <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### column {#a50828bf79317ddff0b210023624b99ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::column</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 254 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a50828bf79317ddff0b210023624b99ff">254</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a50828bf79317ddff0b210023624b99ff">column</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> and <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>.
</div>
</div>

### deleteStream {#afcb58d2742ea23b5da0bbe3264d4f803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::CharStream::deleteStream</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 264 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcb58d2742ea23b5da0bbe3264d4f803">264</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">               <a href="#afcb58d2742ea23b5da0bbe3264d4f803">deleteStream</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a> and <a href="#ab4fb67513988560781f46bb5124f7966">\~CharStream</a>.
</div>
</div>

### inBuf {#afc3a2cee410152b326e23831f1f32453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::inBuf</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 260 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc3a2cee410152b326e23831f1f32453">260</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#afc3a2cee410152b326e23831f1f32453">inBuf</a>;</span></span></div>

</div>


Referenced by <a href="#aea30b248a3b05857e3e60101afd2617a">backup</a>, <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a> and <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### inputStream {#ae43ed68c768f19eb4a9bf8c393d9fb1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReaderStream* vhdl::parser::CharStream::inputStream</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 263 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">263</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/readerstream">ReaderStream</a>*      <a href="#ae43ed68c768f19eb4a9bf8c393d9fb1d">inputStream</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a> and <a href="#ab4fb67513988560781f46bb5124f7966">\~CharStream</a>.
</div>
</div>

### line {#a1ec713a583a0ff2f32092c39101d14cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::line</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 255 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ec713a583a0ff2f32092c39101d14cb">255</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a1ec713a583a0ff2f32092c39101d14cb">line</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> and <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>.
</div>
</div>

### maxNextCharInd {#a255ae084850ea92b02b420078c283490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::maxNextCharInd</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 259 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a255ae084850ea92b02b420078c283490">259</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a255ae084850ea92b02b420078c283490">maxNextCharInd</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a6a84b589f280fbac29dbb2325196bb05">endOfInput</a> and <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a>.
</div>
</div>

### prevCharIsCR {#a3896c04ca5e2e67a6d6d76850c89ef54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::CharStream::prevCharIsCR</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 256 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3896c04ca5e2e67a6d6d76850c89ef54">256</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">               <a href="#a3896c04ca5e2e67a6d6d76850c89ef54">prevCharIsCR</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> and <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>.
</div>
</div>

### prevCharIsLF {#ab6180061e753afda80477ce049c9fa64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::CharStream::prevCharIsLF</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 257 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6180061e753afda80477ce049c9fa64">257</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">               <a href="#ab6180061e753afda80477ce049c9fa64">prevCharIsLF</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a> and <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>.
</div>
</div>

### tabSize {#a53d2f0014c25f1bc4f8b94bba8659dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::tabSize</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 261 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53d2f0014c25f1bc4f8b94bba8659dec">261</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#a53d2f0014c25f1bc4f8b94bba8659dec">tabSize</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#ad61bba1ec964d0ca48f36f71c7c465e3">getTabSize</a> and <a href="#a3b9ca593901a797f6076230835b64b08">setTabSize</a>.
</div>
</div>

### tokenBegin {#aa9408d80c650063cb31f81c9a6cd590e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::CharStream::tokenBegin</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 253 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9408d80c650063cb31f81c9a6cd590e">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                <a href="#aa9408d80c650063cb31f81c9a6cd590e">tokenBegin</a>;</span></span></div>

</div>


Referenced by <a href="#a4550db4daa4e8ec748659002ddb2ad6c">BeginToken</a>, <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a3e0f2c3e5fa9250abf00696661639488">getBeginColumn</a>, <a href="#a3f296517fa30b9728af5ec8a9417800d">getBeginLine</a> and <a href="#a4c4e17dcc7575e75150471e38531e7d2">GetImage</a>.
</div>
</div>

### trackLineColumn {#a0d812351e15796fd8ea5bb48257794a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::CharStream::trackLineColumn</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 262 of file <a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d812351e15796fd8ea5bb48257794a4">262</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">               <a href="#a0d812351e15796fd8ea5bb48257794a4">trackLineColumn</a>;</span></span></div>

</div>


Referenced by <a href="#a242b0ade90665d38c5931af90a59038b">CharStream</a>, <a href="#ac16b96fc00c5fe1c7587406d6869f9b5">CharStream</a>, <a href="#a0582344d99aae18c75c7524f7b5a98b8">CharStream</a>, <a href="#ac868943acf237740db51babde94cff7b">CharStream</a>, <a href="#a82949d505a06f19999787ee61f85f7a7">CharStream</a>, <a href="#a7a3b115d9cb6f671539a8db6630f515c">CharStream</a>, <a href="#a3da31e2203a8bcdf92b4726e83535104">CharStream</a>, <a href="#a36665c2174fbfd9d427d35f2babbd818">getBufcolumn</a>, <a href="#aacc5ee96e0b1352acc4acde5a0e23aca">getBufline</a>, <a href="#aa34c97a27cde33d957e4f6eaabb025b1">getTrackLineColumn</a>, <a href="#a9973e74a1dc5b4e1a99139b638286c42">readChar</a> and <a href="#a12712c9866fb3495782fc0f28994d4d9">setTrackLineColumn</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/charstream-h">CharStream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
