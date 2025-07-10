---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/htmlentitymapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HtmlEntityMapper` Class Reference

<p>Singleton helper class to map html entities to other formats. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlEntityMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htmlentity-h">src/htmlentity.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SymType { <a href="#a5fa49b07f0b74254ab5bd5b18474d7df">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PerlType { <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb3bfaff647723db532f2dec86d446e">~HtmlEntityMapper</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c3a82ead9d9f041131d3bf6ebf9f35">name2sym</a> (const QCString &amp;symName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give code of the requested HTML entity name. <a href="#af0c3a82ead9d9f041131d3bf6ebf9f35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a01097bbc33683b24dc0ddd198f958">utf8</a> (SymType symb, bool useInPrintf=FALSE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the UTF8 code of the HTML entity. <a href="#ad8a01097bbc33683b24dc0ddd198f958">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea40dae4575be9010f2ea950206a6f57">html</a> (SymType symb, bool useInPrintf=FALSE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the html code of the HTML entity. <a href="#aea40dae4575be9010f2ea950206a6f57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6359802a6779aa5f0245357d974c3bd1">xml</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the XML code of the HTML entity. <a href="#a6359802a6779aa5f0245357d974c3bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfca10f028c7820564bbd80728898a79">docbook</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the docbook code of the HTML entity. <a href="#acfca10f028c7820564bbd80728898a79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401769ae867a274591c49695c3a819f0">latex</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the LaTeX code of the HTML entity. <a href="#a401769ae867a274591c49695c3a819f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69bb690ab38e84854b912b68e71cf79">man</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the man code of the HTML entity. <a href="#ae69bb690ab38e84854b912b68e71cf79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e02cf0591dcb069b71e93f3e827a36c">rtf</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the RTF code of the HTML entity. <a href="#a9e02cf0591dcb069b71e93f3e827a36c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/htmlentitymapper/perlsymb">PerlSymb</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d4e0e2e83a943ea25985c0792f71b0">perl</a> (SymType symb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access routine to the perl struct with the perl code of the HTML entity. <a href="#a56d4e0e2e83a943ea25985c0792f71b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7b82a1151c72c7df57732517379a14">writeXMLSchema</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80b42ee1d05037eed6e1c88bc844ece">validate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Routine to check if the entries of the html_entities are numbered correctly. <a href="#ac80b42ee1d05037eed6e1c88bc844ece">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/htmlentitymapper">HtmlEntityMapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9170301bb5ed20abd90f396a53e3e1f7">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the one and only instance of the HTML entity mapper. <a href="#a9170301bb5ed20abd90f396a53e3e1f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/htmlentitymapper">HtmlEntityMapper</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7e4a21bf45782d679c588b72189e7b">s_instance</a></td>
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

<p>Singleton helper class to map html entities to other formats.</p>

<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### PerlType {#a4911b3c9af98290f7ee0696fc2c8a6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum HtmlEntityMapper::PerlType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_unknown<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a422e91df358180b024c4ca4b2696d489"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_string<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a24b7e499fed26aa3b8bcb1ebe3f66baa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_char<a id="a4911b3c9af98290f7ee0696fc2c8a6a3ad04402fe2918b7724f6516397fa0d1a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_symbol<a id="a4911b3c9af98290f7ee0696fc2c8a6a3ac53b4e827b1f114aa86816a09ad0957f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_umlaut<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a0a746987126a0652f79f06fadae9cffd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_acute<a id="a4911b3c9af98290f7ee0696fc2c8a6a3afedd610e97f6262280751ca949693d82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_grave<a id="a4911b3c9af98290f7ee0696fc2c8a6a3aab7eb5ca6b0f7f32246afe98f093c77c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_circ<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a20f5cf2207ec7f589aa4549967177903"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_slash<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a506894a243e06e65383f6b5bb9035944"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_tilde<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a1f7beea596e018c2e12fcd34bb923214"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_cedilla<a id="a4911b3c9af98290f7ee0696fc2c8a6a3a2559915a1e26ef534de86d474925e6ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Perl_ring<a id="a4911b3c9af98290f7ee0696fc2c8a6a3af7748fc167a6ee4dbf84a122ee9d40a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4911b3c9af98290f7ee0696fc2c8a6a3ad04402fe2918b7724f6516397fa0d1a3">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3">PerlType</a> { <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a422e91df358180b024c4ca4b2696d489">Perl_unknown</a> = 0, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a24b7e499fed26aa3b8bcb1ebe3f66baa">Perl_string</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3ad04402fe2918b7724f6516397fa0d1a3">Perl_char</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3ac53b4e827b1f114aa86816a09ad0957f">Perl_symbol</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a0a746987126a0652f79f06fadae9cffd">Perl_umlaut</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4911b3c9af98290f7ee0696fc2c8a6a3afedd610e97f6262280751ca949693d82">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3afedd610e97f6262280751ca949693d82">Perl_acute</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3aab7eb5ca6b0f7f32246afe98f093c77c">Perl_grave</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a20f5cf2207ec7f589aa4549967177903">Perl_circ</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a506894a243e06e65383f6b5bb9035944">Perl_slash</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a1f7beea596e018c2e12fcd34bb923214">Perl_tilde</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a2559915a1e26ef534de86d474925e6ed">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a2559915a1e26ef534de86d474925e6ed">Perl_cedilla</a>, <a href="#a4911b3c9af98290f7ee0696fc2c8a6a3af7748fc167a6ee4dbf84a122ee9d40a3">Perl_ring</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">                  };</span></span></div>

</div>

</div>
</div>

### SymType {#a5fa49b07f0b74254ab5bd5b18474d7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum HtmlEntityMapper::SymType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Unknown<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_nbsp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadbf07f59ac6dd9b95d62f8ef9774df54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_iexcl<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa68c10a4622a7cbb71f2ec823da85b5b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_cent<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa93724454fe23441fce7cf021f5f5c541"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_pound<a id="a5fa49b07f0b74254ab5bd5b18474d7dfafe7250dea3cd2297c57f7e04d38ab6fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_curren<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6807b262b87437bbbe9362cfa48725a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_yen<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa009456a9fdac8fdc842094eca794fb5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_brvbar<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaedc86f6537b72e15f91e60bab75deabd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sect<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1c180347c8be4c00c38af3592b3cf026"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_uml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa463a4f287863938d7be46ffa56e86d1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_copy<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3227545d490d9698132a2ece32d7740e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ordf<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9b54c6eecb1d5af3019891b2106e47a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_laquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa155821304bb2f964f603caa8c9c2dfb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_not<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac882d6b7f69cfe3b8ce25848a3e42d5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_shy<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa810f3a162d144a42a122053e976f0171"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_reg<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5557d19c8d1c1ff6ff78448fdd747913"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_macr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1e5e9df75acb9275703afa0a982068ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_deg<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae868c47d7f176c2eb97d386d47c4c2f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_plusmn<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2973fd0cd9422dd855e8b23f39ac3b27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sup2<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa51c2f07be2ba378eb14297632be7e652"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sup3<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa74285286592e8b53f0d3cb44f85c16d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_acute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf8840ed4bcdcf8306c3c4237835dc97b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_micro<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac69361995d9ea410cb8a952325172f79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_para<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa77fbafccce0153cc408ea0f3ec2da222"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_middot<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac4a38c60d178277f1c1ae81bba90a54c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_cedil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa275c92c919d9d5468d35818b2ae466db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sup1<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0f526bfc6f3b54978faa228792d76350"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ordm<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa79f18ab70256445f9f5fe44f9db7368b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_raquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf24ddc3c4aa78bec7dc42b770dec614b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_frac14<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa64d2cffb62023619ac7bbbcb51dda2c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_frac12<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab1b913b9900383f804c6d97ca40a2a24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_frac34<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadbb621a01db93ede733ebd125ddb37b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_iquest<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa591d734c54de37a25a7c03fd9687bc90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Agrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa9a810d6db4ef8d688671e0a4bc01de9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Aacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3e183f9aecd05984816a60b95d41ba76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Acirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaede6fd42339cc67835bbee7eee3b31fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Atilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0600309b5954f6748f57a1aa3ec0e82f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Auml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfada8bcd5fcf322c1704ab42118b1cd847"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Aring<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3a20868abd7a7969c9a2c6513a69f204"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_AElig<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa324b2f6ff54dd4a14a97bd942b3b3bcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ccedil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa35c5946f2c1d6dc703d6464da000fc32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Egrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4c472c4e703c715f39f475af051182fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Eacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0c3658ee1d3c4dd33c33caf3df8c3be6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ecirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0e4f1d72e590600d993c6b4e42150b5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Euml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa11865b3ca833cf00f2017e09bd10e65d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Igrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2056cf4b994e7015f77383b08cf24de3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Iacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa825073ca49b848bfacc3708d31bac6cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Icirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac20aed748e18b7b71cfbcb6a5fcdbbbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Iuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0cdb2ffcbc3f6a74db6506f053cb9100"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ETH<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab6ae3557d2aa1e37a35d3a470320d594"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ntilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9ad2ce8547fae73d54eb70c966bb147e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ograve<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5a1ac942329934819bb5ae48d782c558"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Oacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac436d3438120291f612b9ef50ba5aae4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ocirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4b3a87f2c2f3cbc00103d0d98ab06c11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Otilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad2b6fe95d945fb8b2064f43142856387"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ouml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa156440cff15651158bfaf1dd111f2942"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_times<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa61237017e187b678fa480a84ff591956"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Oslash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa711ab2071c62f4953b4fc0289f28e5b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ugrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa43fab0cd9235a333e997990afa292618"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Uacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf487b7c0d8abb346bd0d50c2bad176b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Ucirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8c53981bbdb1da8a288e73fc391dc5b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Uuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa849f2a219ee9a7a925563cc7d2159b14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Yacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8f1820ef603124c96fc3654659e64a70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_THORN<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadcc5a9da0e555e8c4dac43c6d52fa7bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_szlig<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa292caf990628d45d1be2f5a3a361e7a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_agrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa89d97482bc5df3abaf1ea1ba3d1c96e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_aacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0b4f3db772bbf3e039c9dfabfd5aafab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_acirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5ae64d10b95a40572e204b5ff021eb65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_atilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6d23164ec47e48284c6e2b9aa64a63fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_auml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa554b611760b104b3ccd9dcca34aead21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_aring<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae8b4856ddf339c085bedcf21ce61f20f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_aelig<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab7dc51cca013d2b7d18f9b3826f1742e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ccedil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7504107ed0bc16ae8a230ca2c9b44cf5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_egrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad215374e498a0a4339f59a416edd2a37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_eacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae2d1c8419348efc6e4530ee7af5ff69a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ecirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab91711a318d02c61d67517e9a0d00f55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_euml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa50363c4474aa5d25991d28b8e50d6a99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_igrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0e274be2346215c36a178a91870b51bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_iacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfacfa2fa96efe98b328a335766692d2296"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_icirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfada87f1b70189d73eb6498a8399ab2020"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_iuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf69993250771108255caaeb2830e029f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_eth<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1f5bf3646eb303c58adca39a486b7320"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ntilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3ae84d85a5f94cb2bbd300884c239488"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ograve<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab9b92cf0f7cb42f2190cb4a319e4495b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_oacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1f74677f3aaa5c8910a473fddb3fdf8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ocirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1ca36cd81b81b1f02c6a2d47c065bd16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_otilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaee8782944ec589c3b8b913b3325c217e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ouml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa66e263fa7c024b96d0f3491e8acfe963"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_divide<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa65b166d2d0ae34a8b1252b3853139289"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_oslash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2b885abb31b7b0459ddb415fb9754926"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ugrave<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa75280ed708bf239ddc8e0a67ff3f0a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_uacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac4db254edb75fdadf767868750b5ee37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ucirc<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaff139457b3b4378ba69787a58e3b45bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_uuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf6e620340fc0878faf670d1ddce612f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_yacute<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae09edef94df903d9a63b7e6c1dc85f0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_thorn<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa49c164125b66b031ab44db48bf0adaa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_yuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa81a0dccf20bbb8841f163e742451d96f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_fnof<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac3fc8e96593f05f23d3bec33d44d0b70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Alpha<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa966dee97d75a4adcb98d5e5497507bd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Beta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaff3cfcd343bdcd1e26ba28f97cabe64d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Gamma<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadd13ab482b6adc6b1fb7fae299b92e34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Delta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa444bcc62b8ff41f8fc79ea40568f1e2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Epsilon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa339f0da21be0685dcc067983707529be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Zeta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad75184b4f30cfca8c430dd319585e2ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Eta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae1a3ca12f104f84feca455a98beb9b5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Theta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa44490d950ba26526c960048fb8ef5372"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Iota<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac35b52d062cdc8466e73c794bd83868a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Kappa<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa207540c85e21dd3eca4a1ebdd8b69987"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Lambda<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa822da5b8d36798acac10dbb507b60b5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Mu<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8a5342be0613e8e638b8bb622ff5f814"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Nu<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4dc3801719cf9f2c91e190dea960a71e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Xi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab2c479beb0b3dfcc5159648484f7d1d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Omicron<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa17cfffa6581fb4819982e1ac9b2125e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Pi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa0245937c6e3c698b79de0eca1965339"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Rho<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6e67dab089f6ab8494ef43a7005948a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Sigma<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa901abfc56df0a23313b7fe4a582a138a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Tau<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4d469c91cf171349c3113b9460a6d432"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Upsilon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa13c0ea2505ca7294e51b568e9de6cd38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Phi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9d2b3ff7b819673105e1a3f28637e878"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Chi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa211e96a3ca0d84f0a8575dfcd0113ec5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Psi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4024836b44f7905a9fcb879728490054"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Omega<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa575989ed18c6034e3fb1730268ea4e8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_alpha<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0b9796c7d51e75570aec57b0d047308b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_beta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9b6f572ee040aff6c9f1eddbb618a4e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_gamma<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8d18b842431f9ade0db252afceea42f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_delta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa60b0c548b4cb69085cd34bf7fc85d5bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_epsilon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5bd77e261e5e41851a259a81ac71f825"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_zeta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7f6aba1e6b6585492d9f5c121e6f8813"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_eta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf87f82d5f3d49f677ce5ea9935ea2eb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_theta<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa43c0a2f166dad141aa6961e4291ddb4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_iota<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2202cd8c26b6784f77ca2a1bbe57be17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_kappa<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa98df412747b5016a43f6e5aaab0cd7dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lambda<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3b668e2ec7c18a865f23213e23ff5058"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_mu<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa327b8d93126328584e24cafeb6afedb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_nu<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa653d16d8aded548ce2368ec38bd5464c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_xi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa32bbf322de44ac230353874bb9a637c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_omicron<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac93fd93b9bae622f71ea929c6a032c8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_pi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa040c17a176783933e11dbf9e78a5cf87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rho<a id="a5fa49b07f0b74254ab5bd5b18474d7dfacaf2eb737f05b453dc820fad46b01bee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sigmaf<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf7d0a4e4c95a6ee9275d55baa9caa9a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sigma<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa800a9b2c96f6c8eab3b3a3f43545762e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_tau<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaaceb857ae751c2120c1131b05c4ca8d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_upsilon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaaec3a78aa385aad722309296ce365ad9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_phi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7fecfd3d34bfd4bd018beb666451a7eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_chi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4ec8762e59bc43531e25361498d85225"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_psi<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8fda794d3ae515fd7d683e631b5bea84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_omega<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa879514ab10612b7642eca4a0f8234e8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_thetasym<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac11e62bbb41602e46b3a542418206391"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_upsih<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae5490d1cd72bd96eb7d1ffd800e069b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_piv<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6bb55b21bbdf4d07acb4f64e8e6bfc18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_bull<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7b07c51331df710bf1bf7b5337ca1bde"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_hellip<a id="a5fa49b07f0b74254ab5bd5b18474d7dfabe3a4b370f16ef5514037ffd5dba2835"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_prime<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2ea15fb91c2c2b5578d80994a4511257"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Prime<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa48caa9cf561b8cfc77fb7810a49a168d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_oline<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf426fa3135b6fad19db2b716b62914c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_frasl<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6519990364bb3edd6f296b713f220a4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_weierp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab9924b00ba145fb5916b3b4bec71f61e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_image<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadf51691d90d44f2cd6c833afb8339e76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_real<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad448b50ef60db950fbe018021db1f35e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_trade<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae6f0e647dc49fcc889011dac86c052b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_alefsym<a id="a5fa49b07f0b74254ab5bd5b18474d7dfafa5c64b20099593c23b5eb86722e50a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_larr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa15eb8d91e7f9f6bb3115d9d36b63e9c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_uarr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa27679887d8552ba2443448b70452a674"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rarr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab64775696bd13f3653c77cb53a511338"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_darr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa4218a9be4ed7d9c4dabcdd01e9f9697"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_harr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaec6474ed2f1adc1c86d32994fdf13f9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_crarr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5affdeb4661ed0ccbe626fe39b9a10ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lArr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa59c1ed810e91513796fecaa70d9a6fd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_uArr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2f20e2c97aabdaae64d73e3b5ab91c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rArr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0c8862282fb6abb488defffe8a4dafdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_dArr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9d4a51bbd4fb89d8c93fe75fd696ec65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_hArr<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa97171b2668d86651791e68942278f2aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_forall<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0ea679ef6102eccd87b0d487026be0c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_part<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3fd8bb1700d69e06086a793ea19e7474"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_exist<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7dd89f60a0b6de48df4906118f8cb83c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_empty<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8202dba10ccfc617bfaa856d1b68ff64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_nabla<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad2227e0e8a356ce6ef77afc4fdee3961"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_isin<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa2eb68558ff6d50b97f6e62aaaf0c68c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_notin<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf0cc7dca7d5f329dfc96a74e92259f0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ni<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac3d32aef8085d4db31ffb84a5e1b0c04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_prod<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac932e5465e6fecc72831de1fab948eb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sum<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa97da911d143378cc551c3d489a9aea5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_minus<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab4c8d41134ec3b4dc23e8cd7a8cb3db5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lowast<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa72d1df2ddc7f3990a0058b3c06efc16c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_radic<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa30980dc124faca3253d926299ae3b13e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_prop<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa5beb281fe13f737ba4b5ef85167beac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_infin<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaeffa824142b94a508152d8cdcf0cad53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ang<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa976377247b761cad16c26ce5563e6ace"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_and<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa187cb51b1abd38001f63a82bc0d9d06a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_or<a id="a5fa49b07f0b74254ab5bd5b18474d7dfad0a693dee518d5a780d2a71faabce2b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_cap<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2e51571c817c48f8b90cff37508d82bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_cup<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac0cdf2126620ea894127a3f13ae82995"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_int<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1be79f9625518325774fb737d0202868"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_there4<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2ccf2b8b954edaa18610f6fe77cf2dd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sim<a id="a5fa49b07f0b74254ab5bd5b18474d7dfabedd44d547ab1003cc07417b72d9405c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_cong<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae147b3b00a8e8ed80961b44a19eef305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_asymp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa48619657b4f901af490d740e4f847514"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ne<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa260dbbda2487f061098bc3036a49ab13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_equiv<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa4f86f09ab5b6ef88a1268a6a0a08be3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_le<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3ce525ff1dda1f956b36d8ce20f76984"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ge<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa3088fb5a0aa494b86602711dec45a3c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sub<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa97e2ad2429cf2ce6f78ac57386d815a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sup<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa58e1d46efeab7255e3e815634b69247e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_nsub<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1d9b3c318d86aa45f52e6107399e0c3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sube<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac0f924a87e3d5f13a8da362f6a3c01c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_supe<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa61ba58cd49027191bba21035d98f2be9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_oplus<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab929e40d2fc8321508a510ca17d19b9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_otimes<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa026b4ca9e57c89bc2ba936f76638b22d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_perp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa61534a7b5bf090ed79d69685733865df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sdot<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa098ce1aca1e207f187b56dc5d3557925"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lceil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9b8510c7258472dea0d2993d9df7c154"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rceil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf42b331eba72529aea9dd8e5c4964a44"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lfloor<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf036272bb3b1024a75e1ac40a34cdacc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rfloor<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa774628950a61460f3eb9122746d5ca11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lang<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6a3b1b377f5db77f65351e544f356a74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rang<a id="a5fa49b07f0b74254ab5bd5b18474d7dfabbcd866426cb76edd844f8cd2378b1af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_loz<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa76552aaf14d91aa32b85ea853fd7174e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_spades<a id="a5fa49b07f0b74254ab5bd5b18474d7dfafeaf52bda33baf477c4a56f97fc508e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_clubs<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa900b126939925585720ba8d2584989c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_hearts<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa5933a1de741b579420604c979fe89b3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_diams<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa48860fbcc2edbe1a34605494265c83af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_quot<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0da7644128d35fb8c641b144a43d34d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_amp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac9d9895b648ff978ae94a11f9769fa07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lt<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa59d844f331ab9ef2ea09969bd1fe49c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_gt<a id="a5fa49b07f0b74254ab5bd5b18474d7dfab130e51b5fae965ad89d2ad2aec5fd55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_OElig<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4fd79fe0a88e6225a6b8c3b5e7edbbac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_oelig<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac0883defdd457fc3dc87dba19693fe7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Scaron<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa92a76f5b39acc180c5d1d97118f3d3e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_scaron<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaacf8b703bda409c8c9a599326ac043ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Yuml<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa948ef789ad88c5a32fbe5cb453e8f930"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_circ<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1bca23a76f1cfcdab0a84a5eba5f7ae8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_tilde<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8ce686ba7e0ad16b0971f4151b45a6a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ensp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa568a5b8cb4a9ea661c9d93f6b64cb1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_emsp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa6a242d90de91e2f5603b9b445c0c2305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_thinsp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa55e0e0c0fab34c744def93316ee04bcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_zwnj<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa9a9e7c91cabe621bbf93fd2e537e62bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_zwj<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa35ac591ee824276ce27812ef9f45aef1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lrm<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa005c3f8cc9b939256fc3439fcc442fda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rlm<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa236af46b263d42c50c41fdaea2b48371"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ndash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfacd0a3112ce91c54e19fcf8d9ea6bcb4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_mdash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaecc5d1f433c30fe90106c8066d345a34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lsquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae9ce1423dfae39a221c4df5f3056f872"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rsquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae13a5745a902e5d1cbb2289bc5c8bca5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_sbquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae5711de44363c5e639538bc257ab6920"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_ldquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2c87ad26fe550a1d72d67d37702efb11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rdquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfadc8875237c61592838eb3add21fd79bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_bdquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaa5a7988f0ded24760549a3f45913ffa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_dagger<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaff655367505855f3cdf2768be2cc2d89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Dagger<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac68c43bd2e002a1f995272fbcacd8870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_permil<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8fb32019048d2e6edda7206024094c58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_lsaquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa4fc591d593859e3c85e0c8dcb017ee09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_rsaquo<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa0cfe0a6fee085b925fe6a74c9c1e3f86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_euro<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa2990128b698fa3bca4b57c795701316a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_tm<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa319d09480eab712a1382b506cfdb8265"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_apos<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7c965001eaf24f767fd6459378117aa3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_BSlash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_At<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Less<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Greater<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Amp<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Dollar<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Hash<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_DoubleColon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Percent<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Pipe<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaaf204a8bef3862d9ddddf384b74a62b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Quot<a id="a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Minus<a id="a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Plus<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Dot<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Colon<a id="a5fa49b07f0b74254ab5bd5b18474d7dfa31c6bdded6df8a6f268e3dfb79c224cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Equal<a id="a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Exclam<a id="a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sym_Quest<a id="a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> { <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">Sym_Unknown</a> = -1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa93724454fe23441fce7cf021f5f5c541">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadbf07f59ac6dd9b95d62f8ef9774df54">Sym_nbsp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa68c10a4622a7cbb71f2ec823da85b5b5">Sym_iexcl</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa93724454fe23441fce7cf021f5f5c541">Sym_cent</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfafe7250dea3cd2297c57f7e04d38ab6fe">Sym_pound</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6807b262b87437bbbe9362cfa48725a1">Sym_curren</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaedc86f6537b72e15f91e60bab75deabd">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa009456a9fdac8fdc842094eca794fb5f">Sym_yen</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaedc86f6537b72e15f91e60bab75deabd">Sym_brvbar</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1c180347c8be4c00c38af3592b3cf026">Sym_sect</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa463a4f287863938d7be46ffa56e86d1e">Sym_uml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3227545d490d9698132a2ece32d7740e">Sym_copy</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa155821304bb2f964f603caa8c9c2dfb1">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9b54c6eecb1d5af3019891b2106e47a4">Sym_ordf</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa155821304bb2f964f603caa8c9c2dfb1">Sym_laquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac882d6b7f69cfe3b8ce25848a3e42d5b">Sym_not</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa810f3a162d144a42a122053e976f0171">Sym_shy</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5557d19c8d1c1ff6ff78448fdd747913">Sym_reg</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae868c47d7f176c2eb97d386d47c4c2f2">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1e5e9df75acb9275703afa0a982068ab">Sym_macr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae868c47d7f176c2eb97d386d47c4c2f2">Sym_deg</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2973fd0cd9422dd855e8b23f39ac3b27">Sym_plusmn</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa51c2f07be2ba378eb14297632be7e652">Sym_sup2</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa74285286592e8b53f0d3cb44f85c16d2">Sym_sup3</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf8840ed4bcdcf8306c3c4237835dc97b">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf8840ed4bcdcf8306c3c4237835dc97b">Sym_acute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac69361995d9ea410cb8a952325172f79">Sym_micro</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa77fbafccce0153cc408ea0f3ec2da222">Sym_para</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac4a38c60d178277f1c1ae81bba90a54c">Sym_middot</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa275c92c919d9d5468d35818b2ae466db">Sym_cedil</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab1b913b9900383f804c6d97ca40a2a24">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0f526bfc6f3b54978faa228792d76350">Sym_sup1</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa79f18ab70256445f9f5fe44f9db7368b">Sym_ordm</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf24ddc3c4aa78bec7dc42b770dec614b">Sym_raquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa64d2cffb62023619ac7bbbcb51dda2c8">Sym_frac14</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab1b913b9900383f804c6d97ca40a2a24">Sym_frac12</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3e183f9aecd05984816a60b95d41ba76">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadbb621a01db93ede733ebd125ddb37b6">Sym_frac34</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa591d734c54de37a25a7c03fd9687bc90">Sym_iquest</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa9a810d6db4ef8d688671e0a4bc01de9">Sym_Agrave</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3e183f9aecd05984816a60b95d41ba76">Sym_Aacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaede6fd42339cc67835bbee7eee3b31fa">Sym_Acirc</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa324b2f6ff54dd4a14a97bd942b3b3bcc">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0600309b5954f6748f57a1aa3ec0e82f">Sym_Atilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfada8bcd5fcf322c1704ab42118b1cd847">Sym_Auml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3a20868abd7a7969c9a2c6513a69f204">Sym_Aring</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa324b2f6ff54dd4a14a97bd942b3b3bcc">Sym_AElig</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa35c5946f2c1d6dc703d6464da000fc32">Sym_Ccedil</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0c3658ee1d3c4dd33c33caf3df8c3be6">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4c472c4e703c715f39f475af051182fd">Sym_Egrave</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0c3658ee1d3c4dd33c33caf3df8c3be6">Sym_Eacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0e4f1d72e590600d993c6b4e42150b5b">Sym_Ecirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa11865b3ca833cf00f2017e09bd10e65d">Sym_Euml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2056cf4b994e7015f77383b08cf24de3">Sym_Igrave</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab6ae3557d2aa1e37a35d3a470320d594">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa825073ca49b848bfacc3708d31bac6cc">Sym_Iacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac20aed748e18b7b71cfbcb6a5fcdbbbb">Sym_Icirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0cdb2ffcbc3f6a74db6506f053cb9100">Sym_Iuml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab6ae3557d2aa1e37a35d3a470320d594">Sym_ETH</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9ad2ce8547fae73d54eb70c966bb147e">Sym_Ntilde</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac436d3438120291f612b9ef50ba5aae4">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5a1ac942329934819bb5ae48d782c558">Sym_Ograve</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac436d3438120291f612b9ef50ba5aae4">Sym_Oacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4b3a87f2c2f3cbc00103d0d98ab06c11">Sym_Ocirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad2b6fe95d945fb8b2064f43142856387">Sym_Otilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa156440cff15651158bfaf1dd111f2942">Sym_Ouml</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa711ab2071c62f4953b4fc0289f28e5b7">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa61237017e187b678fa480a84ff591956">Sym_times</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa711ab2071c62f4953b4fc0289f28e5b7">Sym_Oslash</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa43fab0cd9235a333e997990afa292618">Sym_Ugrave</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf487b7c0d8abb346bd0d50c2bad176b7">Sym_Uacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8c53981bbdb1da8a288e73fc391dc5b6">Sym_Ucirc</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa89d97482bc5df3abaf1ea1ba3d1c96e6">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa849f2a219ee9a7a925563cc7d2159b14">Sym_Uuml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8f1820ef603124c96fc3654659e64a70">Sym_Yacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadcc5a9da0e555e8c4dac43c6d52fa7bd">Sym_THORN</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa292caf990628d45d1be2f5a3a361e7a5">Sym_szlig</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa89d97482bc5df3abaf1ea1ba3d1c96e6">Sym_agrave</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0b4f3db772bbf3e039c9dfabfd5aafab">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0b4f3db772bbf3e039c9dfabfd5aafab">Sym_aacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5ae64d10b95a40572e204b5ff021eb65">Sym_acirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6d23164ec47e48284c6e2b9aa64a63fc">Sym_atilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa554b611760b104b3ccd9dcca34aead21">Sym_auml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae8b4856ddf339c085bedcf21ce61f20f">Sym_aring</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab7dc51cca013d2b7d18f9b3826f1742e">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab7dc51cca013d2b7d18f9b3826f1742e">Sym_aelig</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7504107ed0bc16ae8a230ca2c9b44cf5">Sym_ccedil</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad215374e498a0a4339f59a416edd2a37">Sym_egrave</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae2d1c8419348efc6e4530ee7af5ff69a">Sym_eacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab91711a318d02c61d67517e9a0d00f55">Sym_ecirc</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa50363c4474aa5d25991d28b8e50d6a99">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa50363c4474aa5d25991d28b8e50d6a99">Sym_euml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0e274be2346215c36a178a91870b51bd">Sym_igrave</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfacfa2fa96efe98b328a335766692d2296">Sym_iacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfada87f1b70189d73eb6498a8399ab2020">Sym_icirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf69993250771108255caaeb2830e029f">Sym_iuml</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1f5bf3646eb303c58adca39a486b7320">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1f5bf3646eb303c58adca39a486b7320">Sym_eth</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3ae84d85a5f94cb2bbd300884c239488">Sym_ntilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab9b92cf0f7cb42f2190cb4a319e4495b">Sym_ograve</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1f74677f3aaa5c8910a473fddb3fdf8e">Sym_oacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1ca36cd81b81b1f02c6a2d47c065bd16">Sym_ocirc</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa65b166d2d0ae34a8b1252b3853139289">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaee8782944ec589c3b8b913b3325c217e">Sym_otilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa66e263fa7c024b96d0f3491e8acfe963">Sym_ouml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa65b166d2d0ae34a8b1252b3853139289">Sym_divide</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2b885abb31b7b0459ddb415fb9754926">Sym_oslash</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa75280ed708bf239ddc8e0a67ff3f0a6">Sym_ugrave</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa49c164125b66b031ab44db48bf0adaa2">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac4db254edb75fdadf767868750b5ee37">Sym_uacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaff139457b3b4378ba69787a58e3b45bb">Sym_ucirc</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf6e620340fc0878faf670d1ddce612f4">Sym_uuml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae09edef94df903d9a63b7e6c1dc85f0e">Sym_yacute</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa49c164125b66b031ab44db48bf0adaa2">Sym_thorn</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa966dee97d75a4adcb98d5e5497507bd4">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa81a0dccf20bbb8841f163e742451d96f">Sym_yuml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac3fc8e96593f05f23d3bec33d44d0b70">Sym_fnof</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa966dee97d75a4adcb98d5e5497507bd4">Sym_Alpha</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaff3cfcd343bdcd1e26ba28f97cabe64d">Sym_Beta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadd13ab482b6adc6b1fb7fae299b92e34">Sym_Gamma</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa444bcc62b8ff41f8fc79ea40568f1e2b">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa444bcc62b8ff41f8fc79ea40568f1e2b">Sym_Delta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa339f0da21be0685dcc067983707529be">Sym_Epsilon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad75184b4f30cfca8c430dd319585e2ae">Sym_Zeta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae1a3ca12f104f84feca455a98beb9b5e">Sym_Eta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa44490d950ba26526c960048fb8ef5372">Sym_Theta</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac35b52d062cdc8466e73c794bd83868a">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac35b52d062cdc8466e73c794bd83868a">Sym_Iota</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa207540c85e21dd3eca4a1ebdd8b69987">Sym_Kappa</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa822da5b8d36798acac10dbb507b60b5f">Sym_Lambda</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8a5342be0613e8e638b8bb622ff5f814">Sym_Mu</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4dc3801719cf9f2c91e190dea960a71e">Sym_Nu</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa17cfffa6581fb4819982e1ac9b2125e8">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab2c479beb0b3dfcc5159648484f7d1d6">Sym_Xi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa17cfffa6581fb4819982e1ac9b2125e8">Sym_Omicron</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa0245937c6e3c698b79de0eca1965339">Sym_Pi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6e67dab089f6ab8494ef43a7005948a7">Sym_Rho</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa901abfc56df0a23313b7fe4a582a138a">Sym_Sigma</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa211e96a3ca0d84f0a8575dfcd0113ec5">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4d469c91cf171349c3113b9460a6d432">Sym_Tau</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa13c0ea2505ca7294e51b568e9de6cd38">Sym_Upsilon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9d2b3ff7b819673105e1a3f28637e878">Sym_Phi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa211e96a3ca0d84f0a8575dfcd0113ec5">Sym_Chi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4024836b44f7905a9fcb879728490054">Sym_Psi</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0b9796c7d51e75570aec57b0d047308b">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa575989ed18c6034e3fb1730268ea4e8e">Sym_Omega</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0b9796c7d51e75570aec57b0d047308b">Sym_alpha</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9b6f572ee040aff6c9f1eddbb618a4e9">Sym_beta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8d18b842431f9ade0db252afceea42f2">Sym_gamma</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa60b0c548b4cb69085cd34bf7fc85d5bc">Sym_delta</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5bd77e261e5e41851a259a81ac71f825">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5bd77e261e5e41851a259a81ac71f825">Sym_epsilon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7f6aba1e6b6585492d9f5c121e6f8813">Sym_zeta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf87f82d5f3d49f677ce5ea9935ea2eb5">Sym_eta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa43c0a2f166dad141aa6961e4291ddb4">Sym_theta</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2202cd8c26b6784f77ca2a1bbe57be17">Sym_iota</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa98df412747b5016a43f6e5aaab0cd7dd">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa98df412747b5016a43f6e5aaab0cd7dd">Sym_kappa</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3b668e2ec7c18a865f23213e23ff5058">Sym_lambda</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa327b8d93126328584e24cafeb6afedb5">Sym_mu</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa653d16d8aded548ce2368ec38bd5464c">Sym_nu</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa32bbf322de44ac230353874bb9a637c2">Sym_xi</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac93fd93b9bae622f71ea929c6a032c8a">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac93fd93b9bae622f71ea929c6a032c8a">Sym_omicron</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa040c17a176783933e11dbf9e78a5cf87">Sym_pi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfacaf2eb737f05b453dc820fad46b01bee">Sym_rho</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf7d0a4e4c95a6ee9275d55baa9caa9a6">Sym_sigmaf</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa800a9b2c96f6c8eab3b3a3f43545762e">Sym_sigma</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4ec8762e59bc43531e25361498d85225">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaaceb857ae751c2120c1131b05c4ca8d7">Sym_tau</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaaec3a78aa385aad722309296ce365ad9">Sym_upsilon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7fecfd3d34bfd4bd018beb666451a7eb">Sym_phi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4ec8762e59bc43531e25361498d85225">Sym_chi</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8fda794d3ae515fd7d683e631b5bea84">Sym_psi</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7b07c51331df710bf1bf7b5337ca1bde">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa879514ab10612b7642eca4a0f8234e8c">Sym_omega</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac11e62bbb41602e46b3a542418206391">Sym_thetasym</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae5490d1cd72bd96eb7d1ffd800e069b7">Sym_upsih</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6bb55b21bbdf4d07acb4f64e8e6bfc18">Sym_piv</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7b07c51331df710bf1bf7b5337ca1bde">Sym_bull</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6519990364bb3edd6f296b713f220a4d">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfabe3a4b370f16ef5514037ffd5dba2835">Sym_hellip</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2ea15fb91c2c2b5578d80994a4511257">Sym_prime</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa48caa9cf561b8cfc77fb7810a49a168d">Sym_Prime</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf426fa3135b6fad19db2b716b62914c1">Sym_oline</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6519990364bb3edd6f296b713f220a4d">Sym_frasl</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfafa5c64b20099593c23b5eb86722e50a8">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab9924b00ba145fb5916b3b4bec71f61e">Sym_weierp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadf51691d90d44f2cd6c833afb8339e76">Sym_image</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad448b50ef60db950fbe018021db1f35e">Sym_real</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae6f0e647dc49fcc889011dac86c052b5">Sym_trade</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfafa5c64b20099593c23b5eb86722e50a8">Sym_alefsym</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa4218a9be4ed7d9c4dabcdd01e9f9697">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa15eb8d91e7f9f6bb3115d9d36b63e9c8">Sym_larr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa27679887d8552ba2443448b70452a674">Sym_uarr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab64775696bd13f3653c77cb53a511338">Sym_rarr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa4218a9be4ed7d9c4dabcdd01e9f9697">Sym_darr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaec6474ed2f1adc1c86d32994fdf13f9d">Sym_harr</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5affdeb4661ed0ccbe626fe39b9a10ca">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5affdeb4661ed0ccbe626fe39b9a10ca">Sym_crarr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa59c1ed810e91513796fecaa70d9a6fd4">Sym_lArr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2f20e2c97aabdaae64d73e3b5ab91c2b">Sym_uArr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0c8862282fb6abb488defffe8a4dafdc">Sym_rArr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9d4a51bbd4fb89d8c93fe75fd696ec65">Sym_dArr</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8202dba10ccfc617bfaa856d1b68ff64">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa97171b2668d86651791e68942278f2aa">Sym_hArr</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0ea679ef6102eccd87b0d487026be0c8">Sym_forall</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3fd8bb1700d69e06086a793ea19e7474">Sym_part</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7dd89f60a0b6de48df4906118f8cb83c">Sym_exist</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8202dba10ccfc617bfaa856d1b68ff64">Sym_empty</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa2eb68558ff6d50b97f6e62aaaf0c68c">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad2227e0e8a356ce6ef77afc4fdee3961">Sym_nabla</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa2eb68558ff6d50b97f6e62aaaf0c68c">Sym_isin</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf0cc7dca7d5f329dfc96a74e92259f0c">Sym_notin</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac3d32aef8085d4db31ffb84a5e1b0c04">Sym_ni</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac932e5465e6fecc72831de1fab948eb0">Sym_prod</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa72d1df2ddc7f3990a0058b3c06efc16c">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa97da911d143378cc551c3d489a9aea5a">Sym_sum</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab4c8d41134ec3b4dc23e8cd7a8cb3db5">Sym_minus</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa72d1df2ddc7f3990a0058b3c06efc16c">Sym_lowast</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa30980dc124faca3253d926299ae3b13e">Sym_radic</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa5beb281fe13f737ba4b5ef85167beac">Sym_prop</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa187cb51b1abd38001f63a82bc0d9d06a">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaeffa824142b94a508152d8cdcf0cad53">Sym_infin</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa976377247b761cad16c26ce5563e6ace">Sym_ang</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa187cb51b1abd38001f63a82bc0d9d06a">Sym_and</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfad0a693dee518d5a780d2a71faabce2b7">Sym_or</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2e51571c817c48f8b90cff37508d82bb">Sym_cap</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae147b3b00a8e8ed80961b44a19eef305">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac0cdf2126620ea894127a3f13ae82995">Sym_cup</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1be79f9625518325774fb737d0202868">Sym_int</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2ccf2b8b954edaa18610f6fe77cf2dd6">Sym_there4</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfabedd44d547ab1003cc07417b72d9405c">Sym_sim</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae147b3b00a8e8ed80961b44a19eef305">Sym_cong</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa48619657b4f901af490d740e4f847514">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa48619657b4f901af490d740e4f847514">Sym_asymp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa260dbbda2487f061098bc3036a49ab13">Sym_ne</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa4f86f09ab5b6ef88a1268a6a0a08be3">Sym_equiv</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3ce525ff1dda1f956b36d8ce20f76984">Sym_le</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa3088fb5a0aa494b86602711dec45a3c9">Sym_ge</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1d9b3c318d86aa45f52e6107399e0c3c">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa97e2ad2429cf2ce6f78ac57386d815a5">Sym_sub</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa58e1d46efeab7255e3e815634b69247e">Sym_sup</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1d9b3c318d86aa45f52e6107399e0c3c">Sym_nsub</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac0f924a87e3d5f13a8da362f6a3c01c1">Sym_sube</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa61ba58cd49027191bba21035d98f2be9">Sym_supe</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9b8510c7258472dea0d2993d9df7c154">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab929e40d2fc8321508a510ca17d19b9c">Sym_oplus</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa026b4ca9e57c89bc2ba936f76638b22d">Sym_otimes</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa61534a7b5bf090ed79d69685733865df">Sym_perp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa098ce1aca1e207f187b56dc5d3557925">Sym_sdot</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9b8510c7258472dea0d2993d9df7c154">Sym_lceil</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6a3b1b377f5db77f65351e544f356a74">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf42b331eba72529aea9dd8e5c4964a44">Sym_rceil</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf036272bb3b1024a75e1ac40a34cdacc">Sym_lfloor</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa774628950a61460f3eb9122746d5ca11">Sym_rfloor</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6a3b1b377f5db77f65351e544f356a74">Sym_lang</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfabbcd866426cb76edd844f8cd2378b1af">Sym_rang</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa900b126939925585720ba8d2584989c0">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa76552aaf14d91aa32b85ea853fd7174e">Sym_loz</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfafeaf52bda33baf477c4a56f97fc508e8">Sym_spades</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa900b126939925585720ba8d2584989c0">Sym_clubs</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa5933a1de741b579420604c979fe89b3b">Sym_hearts</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa48860fbcc2edbe1a34605494265c83af">Sym_diams</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac9d9895b648ff978ae94a11f9769fa07">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0da7644128d35fb8c641b144a43d34d1">Sym_quot</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac9d9895b648ff978ae94a11f9769fa07">Sym_amp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa59d844f331ab9ef2ea09969bd1fe49c3">Sym_lt</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfab130e51b5fae965ad89d2ad2aec5fd55">Sym_gt</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4fd79fe0a88e6225a6b8c3b5e7edbbac">Sym_OElig</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1bca23a76f1cfcdab0a84a5eba5f7ae8">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac0883defdd457fc3dc87dba19693fe7a">Sym_oelig</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa92a76f5b39acc180c5d1d97118f3d3e8">Sym_Scaron</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaacf8b703bda409c8c9a599326ac043ab">Sym_scaron</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa948ef789ad88c5a32fbe5cb453e8f930">Sym_Yuml</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1bca23a76f1cfcdab0a84a5eba5f7ae8">Sym_circ</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6a242d90de91e2f5603b9b445c0c2305">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8ce686ba7e0ad16b0971f4151b45a6a6">Sym_tilde</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa568a5b8cb4a9ea661c9d93f6b64cb1b">Sym_ensp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa6a242d90de91e2f5603b9b445c0c2305">Sym_emsp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa55e0e0c0fab34c744def93316ee04bcf">Sym_thinsp</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa9a9e7c91cabe621bbf93fd2e537e62bf">Sym_zwnj</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa005c3f8cc9b939256fc3439fcc442fda">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa35ac591ee824276ce27812ef9f45aef1">Sym_zwj</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa005c3f8cc9b939256fc3439fcc442fda">Sym_lrm</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa236af46b263d42c50c41fdaea2b48371">Sym_rlm</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfacd0a3112ce91c54e19fcf8d9ea6bcb4a">Sym_ndash</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaecc5d1f433c30fe90106c8066d345a34">Sym_mdash</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2c87ad26fe550a1d72d67d37702efb11">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae9ce1423dfae39a221c4df5f3056f872">Sym_lsquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae13a5745a902e5d1cbb2289bc5c8bca5">Sym_rsquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae5711de44363c5e639538bc257ab6920">Sym_sbquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2c87ad26fe550a1d72d67d37702efb11">Sym_ldquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfadc8875237c61592838eb3add21fd79bf">Sym_rdquo</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa5a7988f0ded24760549a3f45913ffa5">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaa5a7988f0ded24760549a3f45913ffa5">Sym_bdquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaff655367505855f3cdf2768be2cc2d89">Sym_dagger</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac68c43bd2e002a1f995272fbcacd8870">Sym_Dagger</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8fb32019048d2e6edda7206024094c58">Sym_permil</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4fc591d593859e3c85e0c8dcb017ee09">Sym_lsaquo</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2990128b698fa3bca4b57c795701316a">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa0cfe0a6fee085b925fe6a74c9c1e3f86">Sym_rsaquo</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa2990128b698fa3bca4b57c795701316a">Sym_euro</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">/* doxygen extensions */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7c965001eaf24f767fd6459378117aa3">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa319d09480eab712a1382b506cfdb8265">Sym_tm</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7c965001eaf24f767fd6459378117aa3">Sym_apos</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">/* doxygen commands mapped */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b">Sym_BSlash</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5">Sym_At</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">Sym_Less</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">Sym_Greater</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">Sym_Amp</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">Sym_Dollar</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355">Sym_Hash</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9">Sym_DoubleColon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">Sym_Percent</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaaf204a8bef3862d9ddddf384b74a62b1">Sym_Pipe</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa31c6bdded6df8a6f268e3dfb79c224cf">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10">Sym_Quot</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">Sym_Minus</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42">Sym_Plus</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4">Sym_Dot</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa31c6bdded6df8a6f268e3dfb79c224cf">Sym_Colon</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8">Sym_Equal</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">Sym_Exclam</a>, <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1">Sym_Quest</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">                 };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### HtmlEntityMapper() {#ac16b10159880f0dcd9bf4e0449f7e21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlEntityMapper::HtmlEntityMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 325 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac16b10159880f0dcd9bf4e0449f7e21e">325</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper::HtmlEntityMapper</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entity : <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a>.emplace(entity.item,entity.symb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac80b42ee1d05037eed6e1c88bc844ece">validate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>, <a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a> and <a href="#ac80b42ee1d05037eed6e1c88bc844ece">validate</a>.</p>


<p>Referenced by <a href="#a9170301bb5ed20abd90f396a53e3e1f7">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~HtmlEntityMapper() {#a2fb3bfaff647723db532f2dec86d446e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlEntityMapper::~HtmlEntityMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 334 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fb3bfaff647723db532f2dec86d446e">334</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a2fb3bfaff647723db532f2dec86d446e">HtmlEntityMapper::~HtmlEntityMapper</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### docbook() {#acfca10f028c7820564bbd80728898a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::docbook (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the docbook code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the docbook code of the HTML entity, in case the docbook code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 402 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfca10f028c7820564bbd80728898a79">402</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acfca10f028c7820564bbd80728898a79">HtmlEntityMapper::docbook</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].docbook;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af30a5c4fe2669a2bdb78dd0c964af909">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

### html() {#aea40dae4575be9010f2ea950206a6f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::html (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb, bool useInPrintf=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the html code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">useInPrintf</td>
<td class="doxyParamItemDescription"><p>If TRUE the result will be escaped such that it can be used in a printf string pattern</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the html representation of the HTML entity, in case the html code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 373 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea40dae4575be9010f2ea950206a6f57">373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#aea40dae4575be9010f2ea950206a6f57">HtmlEntityMapper::html</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useInPrintf)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useInPrintf &amp;&amp; symb==<a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym_Percent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"%%"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// escape for printf</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].html;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a> and <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">Sym_Percent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a942ef73e03ae4a8e306dd6e1e98fcd99">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a3af6b81e834fce376849077c0fa6b565">TextDocVisitor::operator()</a>.</p>

</div>
</div>

### latex() {#a401769ae867a274591c49695c3a819f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::latex (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the LaTeX code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the LaTeX code of the HTML entity, in case the LaTeX code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 413 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a401769ae867a274591c49695c3a819f0">413</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a401769ae867a274591c49695c3a819f0">HtmlEntityMapper::latex</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].latex;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a> and <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#abfe122c272f139d98332b7630945da0f">LatexDocVisitor::operator()</a>.</p>

</div>
</div>

### man() {#ae69bb690ab38e84854b912b68e71cf79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::man (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the man code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the man of the HTML entity, in case the man code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 103 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 424 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae69bb690ab38e84854b912b68e71cf79">424</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ae69bb690ab38e84854b912b68e71cf79">HtmlEntityMapper::man</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].man;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/mandocvisitor/#afb7a0185345e8311efd7d18827dbe43b">ManDocVisitor::operator()</a>.</p>

</div>
</div>

### name2sym() {#af0c3a82ead9d9f041131d3bf6ebf9f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlEntityMapper::SymType HtmlEntityMapper::name2sym (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; symName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Give code of the requested HTML entity name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symName</td>
<td class="doxyParamItemDescription"><p>HTML entity name without <span class="doxyComputerOutput">&amp;</span> and <span class="doxyComputerOutput"></span>;</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the code for the requested HTML entity name, in case the requested HTML item does not exist <span class="doxyComputerOutput">HtmlEntityMapper::Sym_unknown</span> is returned.</p></dd>
</dl>


<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 458 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0c3a82ead9d9f041131d3bf6ebf9f35">458</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> <a href="#af0c3a82ead9d9f041131d3bf6ebf9f35">HtmlEntityMapper::name2sym</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;symName)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a>.find(symName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a>.end() ? it-&gt;second : <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">Sym_Unknown</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>.</p>

</div>
</div>

### perl() {#a56d4e0e2e83a943ea25985c0792f71b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HtmlEntityMapper::PerlSymb * HtmlEntityMapper::perl (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the perl struct with the perl code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the pointer to perl struct with the perl code of the HTML entity, in case the perl code does not exists the nullptr pointer is entered in the <span class="doxyComputerOutput">symb</span> field and in the <span class="doxyComputerOutput"><a href="#a4911b3c9af98290f7ee0696fc2c8a6a3a422e91df358180b024c4ca4b2696d489">HtmlEntityMapper::Perl_unknown</a></span> in the <span class="doxyComputerOutput">type</span> field.</p></dd>
</dl>


<p>Declaration at line 110 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 447 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56d4e0e2e83a943ea25985c0792f71b0">447</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/htmlentitymapper/perlsymb">HtmlEntityMapper::PerlSymb</a> *<a href="#a56d4e0e2e83a943ea25985c0792f71b0">HtmlEntityMapper::perl</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].perl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#abcc43541a23f6c0e0bc5c3a25950493b">PerlModDocVisitor::operator()</a>.</p>

</div>
</div>

### rtf() {#a9e02cf0591dcb069b71e93f3e827a36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::rtf (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the RTF code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the RTF of the HTML entity, in case the RTF code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 435 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e02cf0591dcb069b71e93f3e827a36c">435</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9e02cf0591dcb069b71e93f3e827a36c">HtmlEntityMapper::rtf</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].rtf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8123582499bf0458dc938ff66c4724e7">RTFDocVisitor::operator()</a>.</p>

</div>
</div>

### utf8() {#ad8a01097bbc33683b24dc0ddd198f958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::utf8 (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb, bool useInPrintf=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the UTF8 code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">useInPrintf</td>
<td class="doxyParamItemDescription"><p>If TRUE the result will be escaped such that it can be used in a printf string pattern</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the UTF8 code of the HTML entity, in case the UTF code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 353 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8a01097bbc33683b24dc0ddd198f958">353</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ad8a01097bbc33683b24dc0ddd198f958">HtmlEntityMapper::utf8</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useInPrintf)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useInPrintf &amp;&amp; symb==<a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym_Percent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"%%"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// escape for printf</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].UTF8;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a> and <a href="#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">Sym_Percent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a16438c4825791e03c8103b1ffd167c22">PrintDocVisitor::operator()</a>.</p>

</div>
</div>

### writeXMLSchema() {#a7c7b82a1151c72c7df57732517379a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlEntityMapper::writeXMLSchema (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 464 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c7b82a1151c72c7df57732517379a14">464</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bareName = <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[i].xml;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!bareName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; bareName.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight"> &amp;&amp; bareName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"/&gt;"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      bareName = bareName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,bareName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-3); </span><span class="doxyHighlightComment">// strip &lt; and /&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:element name=\""</span><span class="doxyHighlight"> &lt;&lt; bareName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" type=\"docEmptyType\" /&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>.</p>

</div>
</div>

### xml() {#a6359802a6779aa5f0245357d974c3bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * HtmlEntityMapper::xml (<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a> symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access routine to the XML code of the HTML entity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">symb</td>
<td class="doxyParamItemDescription"><p>Code of the requested HTML entity</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the XML code of the HTML entity, in case the XML code is unknown <span class="doxyComputerOutput">nullptr</span> is returned.</p></dd>
</dl>


<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 391 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6359802a6779aa5f0245357d974c3bd1">391</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a6359802a6779aa5f0245357d974c3bd1">HtmlEntityMapper::xml</a>(<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> symb)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>[symb].xml;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ad9f36acc2f17b5a95a12d047ed0f4d08">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### validate() {#ac80b42ee1d05037eed6e1c88bc844ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlEntityMapper::validate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Routine to check if the entries of the html_entities are numbered correctly.</p>


<p>in case of a mismatch a warning message is given.</p>


<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 480 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac80b42ee1d05037eed6e1c88bc844ece">480</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac80b42ee1d05037eed6e1c88bc844ece">HtmlEntityMapper::validate</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entity : <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i != entity.symb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"Internal inconsistency, htmlentries code {} (item={})\n"</span><span class="doxyHighlight">,i,entity.item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp/#addeeaed9ec5e674f6ace6f0ba57b10d7">g_htmlEntities</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>.</p>


<p>Referenced by <a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_name2sym {#a95b999cb7f3b3416a6442d4ad4e5deed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,SymType&gt; HtmlEntityMapper::m_name2sym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a95b999cb7f3b3416a6442d4ad4e5deed">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::</span><span class="doxyHighlightKeywordType">string</span><span class="doxyHighlight">,<a href="#a5fa49b07f0b74254ab5bd5b18474d7df">SymType</a>&gt; <a href="#a95b999cb7f3b3416a6442d4ad4e5deed">m_name2sym</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a> and <a href="#af0c3a82ead9d9f041131d3bf6ebf9f35">name2sym</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a9170301bb5ed20abd90f396a53e3e1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlEntityMapper &amp; HtmlEntityMapper::instance ()</td>
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

<p>Returns the one and only instance of the HTML entity mapper.</p>

<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>, definition at line 339 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9170301bb5ed20abd90f396a53e3e1f7">339</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a> &amp;<a href="#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a> inst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> inst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af30a5c4fe2669a2bdb78dd0c964af909">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a942ef73e03ae4a8e306dd6e1e98fcd99">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#abfe122c272f139d98332b7630945da0f">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#afb7a0185345e8311efd7d18827dbe43b">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#abcc43541a23f6c0e0bc5c3a25950493b">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a16438c4825791e03c8103b1ffd167c22">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8123582499bf0458dc938ff66c4724e7">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a3af6b81e834fce376849077c0fa6b565">TextDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ad9f36acc2f17b5a95a12d047ed0f4d08">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### s\_instance {#afc7e4a21bf45782d679c588b72189e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlEntityMapper* HtmlEntityMapper::s_instance</td>
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



<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc7e4a21bf45782d679c588b72189e7b">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    static <a href="#ac16b10159880f0dcd9bf4e0449f7e21e">HtmlEntityMapper</a> *<a href="#afc7e4a21bf45782d679c588b72189e7b">s_instance</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlentity-cpp">htmlentity.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
