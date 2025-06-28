---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/latexcodegenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LatexCodeGenerator` Class Reference

<p>Generator for LaTeX code fragments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LatexCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/latexgen-h">src/latexgen.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for code generators. <a href="/web-doxygen/docs/api/classes/outputcodeintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator</a> (TextStream *t, const QCString &amp;relPath, const QCString &amp;sourceFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a06015509fb9de74a0948a814b5342">LatexCodeGenerator</a> (TextStream *t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d30e5bd138f1f19515130f7c723abc">setTextStream</a> (TextStream *t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86e44aafce902593c10501dd89026a6">type</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5051bfb4b60ad2ff423818283645d7b7">clone</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a> (const QCString &amp;text) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c4b399e4d3018628e0813c3a92167b">stripCodeComments</a> (bool b) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986a56ec2e0ddaf47a6e3691e9ae720b">startSpecialComment</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e913afc392823753084448f5c62dc6e">endSpecialComment</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4663612155f6cd67929cee3120fa02">setStripIndentAmount</a> (size_t amount) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a72fabfc60a8e24e981a264b27c974d">writeTooltip</a> (const QCString &amp;, const DocLinkInfo &amp;, const QCString &amp;, const QCString &amp;, const SourceLinkInfo &amp;, const SourceLinkInfo &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, int, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfd2b046a17459f69b7d08e49349240">startCodeLine</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8204dc6e2eaa9bcbf319b6ff7eff94">startFontClass</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2817d014a128c1a2bdff10c582e0bfbb">endFontClass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd12f9b880dbe40521022bbc55518f9">writeCodeAnchor</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756ccfff7534033a522196ab842b5f0c">startCodeFragment</a> (const QCString &amp;style) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf84f3e3d479467862d91a7f5ce3b69d">endCodeFragment</a> (const QCString &amp;style) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2465f5c56bd5a837fdb2644a09132ac2">startFold</a> (int, const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05462bfec0ea5fa8a901481b6ea21f3">endFold</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90f342ed41be750ffb1012b7ee08a6b">incUsedTableLevel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2faf2e5a76f8a9162ba70022281bac9">decUsedTableLevel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1f9ea1686cfb3c68bac2bbc5081f55">usedTableLevel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644dfa222652fa561dc841838100115b">setRelativePath</a> (const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8f6f300e6c8de9f20aa3eb9c1024be">setSourceFileName</a> (const QCString &amp;sourceFileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a237438e739e962bba1a51bf41b24a">setInsideTabbing</a> (bool b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac2521a9b24f1a783a729dde02f9bc4">insideTabbing</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393417d1954595842de91c8c33b61b9d">_writeCodeLink</a> (const QCString &amp;className, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b9d4b2f565a9a273859fe0467fe043">docify</a> (const QCString &amp;str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2925f46057294fdec61fd72efc3c6a91">m_streamSet</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14bde2340266057da59c0a5168c57e21">m_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3eec74bf4332c6f238448049a1fb78">m_relPath</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m_insideTabbing</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114e038b94b1d43e2eecb144f1e5b563">m_stripCodeComments</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75979ed7ee6c1eb75b996e2bc370695b">m_stripIndentAmount</a> = 0</td>
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

<p>Generator for LaTeX code fragments.</p>

<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### LatexCodeGenerator() {#a983453f1453adaf5b5bb732c746ea992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexCodeGenerator::LatexCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sourceFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00030">30</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a983453f1453adaf5b5bb732c746ea992">59</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator::LatexCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sourceFileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a14bde2340266057da59c0a5168c57e21">m_t</a>(t), <a href="#ade3eec74bf4332c6f238448049a1fb78">m_relPath</a>(relPath), <a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a>(sourceFileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ade3eec74bf4332c6f238448049a1fb78">m&#95;relPath</a>, <a href="#acc546ace986e41f11d76eb80ec753e04">m&#95;sourceFileName</a> and <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

### LatexCodeGenerator() {#a57a06015509fb9de74a0948a814b5342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexCodeGenerator::LatexCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00031">31</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00064">64</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57a06015509fb9de74a0948a814b5342">64</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator::LatexCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) : <a href="#a14bde2340266057da59c0a5168c57e21">m_t</a>(t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a5051bfb4b60ad2ff423818283645d7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputCodeIntf &gt; LatexCodeGenerator::clone ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00035">35</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5051bfb4b60ad2ff423818283645d7b7">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeIntf&gt; <a href="#a5051bfb4b60ad2ff423818283645d7b7">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;LatexCodeGenerator&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### codify() {#ace27d46d07e19112fc6ee3411915c8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00036">36</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace27d46d07e19112fc6ee3411915c8ea">78</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ace27d46d07e19112fc6ee3411915c8ea">LatexCodeGenerator::codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//char cs[5];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/doxygen-h/#af8556c37f3acfa45992b8697930c501b">THREAD_LOCAL</a> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *result = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/doxygen-h/#af8556c37f3acfa45992b8697930c501b">THREAD_LOCAL</a> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lresult = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightComment">// only update column count</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a>(p,<a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// actually output content and keep track of m_col</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 0x0c: p++;  </span><span class="doxyHighlightComment">// remove ^L</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>&gt;=<a href="#a75979ed7ee6c1eb75b996e2bc370695b">m_stripIndentAmount</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">                       *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; (<a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> ? </span><span class="doxyHighlightStringLiteral">"\\ "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">                     p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">:  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt;</span><span class="doxyHighlightStringLiteral">"\\string^"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">                     p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">:  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt;</span><span class="doxyHighlightStringLiteral">"\\`{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">                     p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> spacesToNextTabStop = tabSize - (<a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (spacesToNextTabStop--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>&gt;=<a href="#a75979ed7ee6c1eb75b996e2bc370695b">m_stripIndentAmount</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">                           *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; (<a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> ? </span><span class="doxyHighlightStringLiteral">"\\ "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">                       p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">                     p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef  COPYCHAR</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlightComment">// helper macro to copy a single utf8 character, dealing with multibyte chars.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define COPYCHAR() do {                                             \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       int bytes = getUTF8CharNumBytes(c);          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       if (lresult &lt; (i + bytes + 1))               \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       {                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                         lresult += 512;                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                         result = static_cast&lt;char *&gt;(realloc(result, lresult)); \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       }                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       for (int j=0; j&lt;bytes &amp;&amp; *p; j++)            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       {                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                         result[i++]=*p++;                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       }                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                       m_col++;                                     \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                     } while(0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">// gather characters until we find whitespace or another special character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a9a7f04a1060dfff4cad9f82379053257">COPYCHAR</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">                              c!=0x0c &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'^'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">                             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a9a7f04a1060dfff4cad9f82379053257">COPYCHAR</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">                       result[i]=0; </span><span class="doxyHighlightComment">// add terminator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/latexgen-h/#a4ee99b7f4c3b954efce5bf4da1518b31">filterLatexString</a>(*<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a>,result,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m_insideTabbing</a>, </span><span class="doxyHighlightComment">// insideTabbing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,  </span><span class="doxyHighlightComment">// insidePre</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// insideItem</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a>&gt;0, </span><span class="doxyHighlightComment">// insideTable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// keepSpaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">                                        );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config&#95;getInt</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a9a7f04a1060dfff4cad9f82379053257">COPYCHAR</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-h/#a4ee99b7f4c3b954efce5bf4da1518b31">filterLatexString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m&#95;col</a>, <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m&#95;doxyCodeLineOpen</a>, <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a>, <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m&#95;insideTabbing</a>, <a href="#a75979ed7ee6c1eb75b996e2bc370695b">m&#95;stripIndentAmount</a>, <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>, <a href="#a76b404ceab074a0a056233427d993224">m&#95;usedTableLevel</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-h/#af8556c37f3acfa45992b8697930c501b">THREAD&#95;LOCAL</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a>.

Referenced by <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a>, <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### decUsedTableLevel() {#aa2faf2e5a76f8a9162ba70022281bac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::decUsedTableLevel ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00065">65</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2faf2e5a76f8a9162ba70022281bac9">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa2faf2e5a76f8a9162ba70022281bac9">decUsedTableLevel</a>() { <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a>--; }</span></span></div>

</div>


Reference <a href="#a76b404ceab074a0a056233427d993224">m&#95;usedTableLevel</a>.
</div>
</div>

### endCodeFragment() {#aaf84f3e3d479467862d91a7f5ce3b69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00308">308</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf84f3e3d479467862d91a7f5ce3b69d">308</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaf84f3e3d479467862d91a7f5ce3b69d">LatexCodeGenerator::endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//endCodeLine checks is there is still an open code line, if so closes it.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{"</span><span class="doxyHighlight"> &lt;&lt; style &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a> and <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

### endCodeLine() {#ad6a36878e0fde7d9d23711fd7487edb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::endCodeLine ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00280">280</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6a36878e0fde7d9d23711fd7487edb8">280</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6a36878e0fde7d9d23711fd7487edb8">LatexCodeGenerator::endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m&#95;doxyCodeLineOpen</a>, <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a> and <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.

Referenced by <a href="#aaf84f3e3d479467862d91a7f5ce3b69d">endCodeFragment</a>.
</div>
</div>

### endFold() {#af05462bfec0ea5fa8a901481b6ea21f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::endFold ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00061">61</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af05462bfec0ea5fa8a901481b6ea21f3">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af05462bfec0ea5fa8a901481b6ea21f3">endFold</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endFontClass() {#a2817d014a128c1a2bdff10c582e0bfbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::endFontClass ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00297">297</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2817d014a128c1a2bdff10c582e0bfbb">297</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2817d014a128c1a2bdff10c582e0bfbb">LatexCodeGenerator::endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a> and <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

### endSpecialComment() {#a6e913afc392823753084448f5c62dc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::endSpecialComment ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00039">39</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00186">186</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e913afc392823753084448f5c62dc6e">186</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e913afc392823753084448f5c62dc6e">LatexCodeGenerator::endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a>.
</div>
</div>

### incUsedTableLevel() {#af90f342ed41be750ffb1012b7ee08a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::incUsedTableLevel ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00064">64</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af90f342ed41be750ffb1012b7ee08a6b">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af90f342ed41be750ffb1012b7ee08a6b">incUsedTableLevel</a>() { <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a>++; }</span></span></div>

</div>


Reference <a href="#a76b404ceab074a0a056233427d993224">m&#95;usedTableLevel</a>.
</div>
</div>

### insideTabbing() {#a2ac2521a9b24f1a783a729dde02f9bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::insideTabbing ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ac2521a9b24f1a783a729dde02f9bc4">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2ac2521a9b24f1a783a729dde02f9bc4">insideTabbing</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m_insideTabbing</a>; }</span></span></div>

</div>


Reference <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m&#95;insideTabbing</a>.
</div>
</div>

### setInsideTabbing() {#a22a237438e739e962bba1a51bf41b24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::setInsideTabbing (bool b)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22a237438e739e962bba1a51bf41b24a">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22a237438e739e962bba1a51bf41b24a">setInsideTabbing</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b) { <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m_insideTabbing</a>=b; }</span></span></div>

</div>


Reference <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m&#95;insideTabbing</a>.
</div>
</div>

### setRelativePath() {#a644dfa222652fa561dc841838100115b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::setRelativePath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a644dfa222652fa561dc841838100115b">68</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a644dfa222652fa561dc841838100115b">LatexCodeGenerator::setRelativePath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ade3eec74bf4332c6f238448049a1fb78">m_relPath</a> = path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ade3eec74bf4332c6f238448049a1fb78">m&#95;relPath</a>.
</div>
</div>

### setSourceFileName() {#a5b8f6f300e6c8de9f20aa3eb9c1024be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::setSourceFileName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sourceFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00073">73</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b8f6f300e6c8de9f20aa3eb9c1024be">73</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b8f6f300e6c8de9f20aa3eb9c1024be">LatexCodeGenerator::setSourceFileName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a> = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#acc546ace986e41f11d76eb80ec753e04">m&#95;sourceFileName</a>.
</div>
</div>

### setStripIndentAmount() {#a1f4663612155f6cd67929cee3120fa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::setStripIndentAmount (size_t amount)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00191">191</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f4663612155f6cd67929cee3120fa02">191</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f4663612155f6cd67929cee3120fa02">LatexCodeGenerator::setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> amount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a75979ed7ee6c1eb75b996e2bc370695b">m_stripIndentAmount</a> = amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a75979ed7ee6c1eb75b996e2bc370695b">m&#95;stripIndentAmount</a>.
</div>
</div>

### setTextStream() {#a54d30e5bd138f1f19515130f7c723abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::setTextStream (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00032">32</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54d30e5bd138f1f19515130f7c723abc">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a54d30e5bd138f1f19515130f7c723abc">setTextStream</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) { <a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> = t; }</span></span></div>

</div>


Reference <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

### startCodeFragment() {#a756ccfff7534033a522196ab842b5f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00303">303</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a756ccfff7534033a522196ab842b5f0c">303</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a756ccfff7534033a522196ab842b5f0c">LatexCodeGenerator::startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{"</span><span class="doxyHighlight"> &lt;&lt; style &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a> and <a href="#a76b404ceab074a0a056233427d993224">m&#95;usedTableLevel</a>.
</div>
</div>

### startCodeLine() {#a8dfd2b046a17459f69b7d08e49349240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::startCodeLine (int)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00053">53</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00269">269</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8dfd2b046a17459f69b7d08e49349240">269</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8dfd2b046a17459f69b7d08e49349240">LatexCodeGenerator::startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\DoxyCodeLine{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m&#95;col</a>, <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m&#95;doxyCodeLineOpen</a>, <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a>, <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### startFold() {#a2465f5c56bd5a837fdb2644a09132ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::startFold (int, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2465f5c56bd5a837fdb2644a09132ac2">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2465f5c56bd5a837fdb2644a09132ac2">startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startFontClass() {#a6d8204dc6e2eaa9bcbf319b6ff7eff94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00291">291</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d8204dc6e2eaa9bcbf319b6ff7eff94">291</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d8204dc6e2eaa9bcbf319b6ff7eff94">LatexCodeGenerator::startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textcolor{"</span><span class="doxyHighlight"> &lt;&lt; name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a> and <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>.
</div>
</div>

### startSpecialComment() {#a986a56ec2e0ddaf47a6e3691e9ae720b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::startSpecialComment ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00038">38</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00181">181</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a986a56ec2e0ddaf47a6e3691e9ae720b">181</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a986a56ec2e0ddaf47a6e3691e9ae720b">LatexCodeGenerator::startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a> = <a href="#a114e038b94b1d43e2eecb144f1e5b563">m_stripCodeComments</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a> and <a href="#a114e038b94b1d43e2eecb144f1e5b563">m&#95;stripCodeComments</a>.
</div>
</div>

### stripCodeComments() {#a70c4b399e4d3018628e0813c3a92167b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::stripCodeComments (bool b)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00037">37</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00176">176</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70c4b399e4d3018628e0813c3a92167b">176</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a70c4b399e4d3018628e0813c3a92167b">LatexCodeGenerator::stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a114e038b94b1d43e2eecb144f1e5b563">m_stripCodeComments</a> = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a114e038b94b1d43e2eecb144f1e5b563">m&#95;stripCodeComments</a>.
</div>
</div>

### type() {#ac86e44aafce902593c10501dd89026a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType LatexCodeGenerator::type ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac86e44aafce902593c10501dd89026a6">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#ac86e44aafce902593c10501dd89026a6">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78">OutputType::Latex</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78">Latex</a>.
</div>
</div>

### usedTableLevel() {#a0f1f9ea1686cfb3c68bac2bbc5081f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LatexCodeGenerator::usedTableLevel ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00066">66</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f1f9ea1686cfb3c68bac2bbc5081f55">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0f1f9ea1686cfb3c68bac2bbc5081f55">usedTableLevel</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a>; }</span></span></div>

</div>


Reference <a href="#a76b404ceab074a0a056233427d993224">m&#95;usedTableLevel</a>.
</div>
</div>

### writeCodeAnchor() {#a9cd12f9b880dbe40521022bbc55518f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cd12f9b880dbe40521022bbc55518f9">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9cd12f9b880dbe40521022bbc55518f9">writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writeCodeLink() {#ae073efd8b440046f245aaff6c56bc1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00041">41</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00196">196</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae073efd8b440046f245aaff6c56bc1f4">196</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae073efd8b440046f245aaff6c56bc1f4">LatexCodeGenerator::writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> usePDFLatex   = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; usePDFLatex &amp;&amp; pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\mbox{\\hyperlink{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m&#95;col</a>, <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a>, <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.

Referenced by <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### writeLineNumber() {#a41b0a17952879ed6de614c8bd4ff6c9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int l, bool writeLineAnchor)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#l00222">222</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41b0a17952879ed6de614c8bd4ff6c9f">222</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">LatexCodeGenerator::writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> usePDFLatex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\DoxyCodeLine{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_BROWSER))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineNumber;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNumber.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%05d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineAnchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      lineAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"_l%05d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      lineAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>(<a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a>, </span><span class="doxyHighlightStringLiteral">".tex"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showTarget = usePDFLatex &amp;&amp; pdfHyperlinks &amp;&amp; !lineAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; writeLineAnchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (showTarget)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\Hypertarget{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(lineAnchor) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca7a1920d61156abc05a60135aefe8bc67">CodeSymbolType::Default</a>,ref,fileName,anchor,lineNumber,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>(lineNumber);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\ "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineNumber;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNumber.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%05d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>(lineNumber);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\ "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m&#95;col</a>, <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m&#95;doxyCodeLineOpen</a>, <a href="#a1d93900983b074fe4382dd6e91420a44">m&#95;hide</a>, <a href="#acc546ace986e41f11d76eb80ec753e04">m&#95;sourceFileName</a>, <a href="#a14bde2340266057da59c0a5168c57e21">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a>.
</div>
</div>

### writeTooltip() {#a2a72fabfc60a8e24e981a264b27c974d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a72fabfc60a8e24e981a264b27c974d">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a72fabfc60a8e24e981a264b27c974d">writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">                     )</span><span class="doxyHighlightKeyword"> override  </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### &#95;writeCodeLink() {#a393417d1954595842de91c8c33b61b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::_writeCodeLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; className, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00074">74</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>
</div>
</div>

### docify() {#a35b9d4b2f565a9a273859fe0467fe043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexCodeGenerator::docify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;col {#a6e3be3cc984b0d52998b0a5095a61aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexCodeGenerator::m_col = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00083">83</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e3be3cc984b0d52998b0a5095a61aac">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a6e3be3cc984b0d52998b0a5095a61aac">m_col</a> = 0;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#a8dfd2b046a17459f69b7d08e49349240">startCodeLine</a>, <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### m&#95;doxyCodeLineOpen {#ae4ad9cdbf89db5b0fc4bcb3da17e6030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::m_doxyCodeLineOpen = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00084">84</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae4ad9cdbf89db5b0fc4bcb3da17e6030">m_doxyCodeLineOpen</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a>, <a href="#a8dfd2b046a17459f69b7d08e49349240">startCodeLine</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### m&#95;hide {#a1d93900983b074fe4382dd6e91420a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00088">88</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d93900983b074fe4382dd6e91420a44">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1d93900983b074fe4382dd6e91420a44">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a>, <a href="#a2817d014a128c1a2bdff10c582e0bfbb">endFontClass</a>, <a href="#a6e913afc392823753084448f5c62dc6e">endSpecialComment</a>, <a href="#a8dfd2b046a17459f69b7d08e49349240">startCodeLine</a>, <a href="#a6d8204dc6e2eaa9bcbf319b6ff7eff94">startFontClass</a>, <a href="#a986a56ec2e0ddaf47a6e3691e9ae720b">startSpecialComment</a>, <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### m&#95;insideTabbing {#aebc26b6a2b2da44df2ab22e1f4a336da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::m_insideTabbing = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00086">86</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebc26b6a2b2da44df2ab22e1f4a336da">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aebc26b6a2b2da44df2ab22e1f4a336da">m_insideTabbing</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#a2ac2521a9b24f1a783a729dde02f9bc4">insideTabbing</a> and <a href="#a22a237438e739e962bba1a51bf41b24a">setInsideTabbing</a>.
</div>
</div>

### m&#95;relPath {#ade3eec74bf4332c6f238448049a1fb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LatexCodeGenerator::m_relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00081">81</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade3eec74bf4332c6f238448049a1fb78">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ade3eec74bf4332c6f238448049a1fb78">m_relPath</a>;</span></span></div>

</div>


Referenced by <a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator</a> and <a href="#a644dfa222652fa561dc841838100115b">setRelativePath</a>.
</div>
</div>

### m&#95;sourceFileName {#acc546ace986e41f11d76eb80ec753e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LatexCodeGenerator::m_sourceFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00082">82</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc546ace986e41f11d76eb80ec753e04">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#acc546ace986e41f11d76eb80ec753e04">m_sourceFileName</a>;</span></span></div>

</div>


Referenced by <a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator</a>, <a href="#a5b8f6f300e6c8de9f20aa3eb9c1024be">setSourceFileName</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### m&#95;streamSet {#a2925f46057294fdec61fd72efc3c6a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::m_streamSet = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00079">79</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2925f46057294fdec61fd72efc3c6a91">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2925f46057294fdec61fd72efc3c6a91">m_streamSet</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### m&#95;stripCodeComments {#a114e038b94b1d43e2eecb144f1e5b563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexCodeGenerator::m_stripCodeComments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00087">87</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a114e038b94b1d43e2eecb144f1e5b563">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a114e038b94b1d43e2eecb144f1e5b563">m_stripCodeComments</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a986a56ec2e0ddaf47a6e3691e9ae720b">startSpecialComment</a> and <a href="#a70c4b399e4d3018628e0813c3a92167b">stripCodeComments</a>.
</div>
</div>

### m&#95;stripIndentAmount {#a75979ed7ee6c1eb75b996e2bc370695b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexCodeGenerator::m_stripIndentAmount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00089">89</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75979ed7ee6c1eb75b996e2bc370695b">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a75979ed7ee6c1eb75b996e2bc370695b">m_stripIndentAmount</a> = 0;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a> and <a href="#a1f4663612155f6cd67929cee3120fa02">setStripIndentAmount</a>.
</div>
</div>

### m&#95;t {#a14bde2340266057da59c0a5168c57e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream* LatexCodeGenerator::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14bde2340266057da59c0a5168c57e21">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *<a href="#a14bde2340266057da59c0a5168c57e21">m_t</a>;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#aaf84f3e3d479467862d91a7f5ce3b69d">endCodeFragment</a>, <a href="#ad6a36878e0fde7d9d23711fd7487edb8">endCodeLine</a>, <a href="#a2817d014a128c1a2bdff10c582e0bfbb">endFontClass</a>, <a href="#a57a06015509fb9de74a0948a814b5342">LatexCodeGenerator</a>, <a href="#a983453f1453adaf5b5bb732c746ea992">LatexCodeGenerator</a>, <a href="#a54d30e5bd138f1f19515130f7c723abc">setTextStream</a>, <a href="#a756ccfff7534033a522196ab842b5f0c">startCodeFragment</a>, <a href="#a8dfd2b046a17459f69b7d08e49349240">startCodeLine</a>, <a href="#a6d8204dc6e2eaa9bcbf319b6ff7eff94">startFontClass</a>, <a href="#ae073efd8b440046f245aaff6c56bc1f4">writeCodeLink</a> and <a href="#a41b0a17952879ed6de614c8bd4ff6c9f">writeLineNumber</a>.
</div>
</div>

### m&#95;usedTableLevel {#a76b404ceab074a0a056233427d993224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LatexCodeGenerator::m_usedTableLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexgen-h/#l00085">85</a> of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76b404ceab074a0a056233427d993224">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a76b404ceab074a0a056233427d993224">m_usedTableLevel</a> = 0;</span></span></div>

</div>


Referenced by <a href="#ace27d46d07e19112fc6ee3411915c8ea">codify</a>, <a href="#aa2faf2e5a76f8a9162ba70022281bac9">decUsedTableLevel</a>, <a href="#af90f342ed41be750ffb1012b7ee08a6b">incUsedTableLevel</a>, <a href="#a756ccfff7534033a522196ab842b5f0c">startCodeFragment</a> and <a href="#a0f1f9ea1686cfb3c68bac2bbc5081f55">usedTableLevel</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
