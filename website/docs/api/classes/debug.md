---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/debug
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Debug` Class Reference

<p>Class containing a print function for diagnostics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class Debug { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/debug-h">src/debug.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugMask : uint64_t { <a href="#a1c3f4696cf44a23f41e034323c426f7d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d002a2d503fa172cc502ccb1198f8c">print_</a> (DebugMask mask, int prio, fmt::string_view fmt, fmt::format_args args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a970761e07475cafdd9fd5395a0c83544">print</a> (DebugMask mask, int prio, fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37b8f08c49a5d316b436e1849dffb9c">setFlagStr</a> (const QCString &amp;label)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb7c17adbcafb5ec252e95c70f12f53">setFlag</a> (const DebugMask mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6226d91e39828116b504b94e22b26b">clearFlag</a> (const DebugMask mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e9401783e852c91f341b3f98198061">isFlagSet</a> (const DebugMask mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d8ac411144a380f838a1766118c6a03">printFlags</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666b610770dd7b7c0a87f2415aefe7d9">setPriority</a> (int p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34e8ad3d814a4cf8b29ce98fd7a96f5">startTimer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc1a68a6e51b015caee0ab90ddb6e87">elapsedTime</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d585549eed6b188844447b6149c576e">curMask</a> = <a href="#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">Debug::Quiet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a> = 0</td>
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

<p>Class containing a print function for diagnostics.</p>

<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DebugMask {#a1c3f4696cf44a23f41e034323c426f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum Debug::DebugMask : uint64_t</td>
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
<td class="doxyEnumItemName">Quiet<a id="a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Preprocessor<a id="a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0001ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CommentCnv<a id="a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0002ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CommentScan<a id="a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0004ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Formula<a id="a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0008ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintTree<a id="a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0010ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Time<a id="a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0020ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtCmd<a id="a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0040ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Markdown<a id="a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0080ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FilterOutput<a id="a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0100ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Plantuml<a id="a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0200ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FortranFixed2Free<a id="a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0400ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cite<a id="a1c3f4696cf44a23f41e034323c426f7da724abc65281c2d47105ebf8a31d6c397"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'0800ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoLineNo<a id="a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'1000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rtf<a id="a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'2000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Qhp<a id="a1c3f4696cf44a23f41e034323c426f7dad9460df52aaeff184624ce6b5a5360e2"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'4000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Tag<a id="a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9"></a></td>
<td class="doxyEnumItemDescription"> (=             0x00'8000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Alias<a id="a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc"></a></td>
<td class="doxyEnumItemDescription"> (=             0x01'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Entries<a id="a1c3f4696cf44a23f41e034323c426f7dad9c34d45743a5b17700d8c98e1fd010c"></a></td>
<td class="doxyEnumItemDescription"> (=             0x02'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sections<a id="a1c3f4696cf44a23f41e034323c426f7da9087db4bb32e89ea9a871a7dd6e69158"></a></td>
<td class="doxyEnumItemDescription"> (=             0x04'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Stderr<a id="a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550"></a></td>
<td class="doxyEnumItemDescription"> (=             0x08'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Layout<a id="a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5"></a></td>
<td class="doxyEnumItemDescription"> (=             0x10'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex<a id="a1c3f4696cf44a23f41e034323c426f7da0c1d42bd6b09e5427669a49f082e823b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'FFFF'FF00'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_code<a id="a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'0100'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_commentcnv<a id="a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'0200'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_commentscan<a id="a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'0400'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_configimpl<a id="a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'0800'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_constexp<a id="a1c3f4696cf44a23f41e034323c426f7dabb929f64e4a2c8c41e79fa5bc4d763f3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'1000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_declinfo<a id="a1c3f4696cf44a23f41e034323c426f7da4fb818b908e028c1bc463472e3959dba"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'2000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_defargs<a id="a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'4000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_doctokenizer<a id="a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0000'8000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_fortrancode<a id="a1c3f4696cf44a23f41e034323c426f7dac254e604d7117b1b02b7a35d96f61714"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0001'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_fortranscanner<a id="a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0002'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_lexcode<a id="a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0004'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_lexscanner<a id="a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0008'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_pre<a id="a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0010'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_pycode<a id="a1c3f4696cf44a23f41e034323c426f7da391da68ca9444e86fc0c86e3b45114da"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0020'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_pyscanner<a id="a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0040'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_scanner<a id="a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0080'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_sqlcode<a id="a1c3f4696cf44a23f41e034323c426f7da646fb0e06016ef0b89e2c998a2d4f510"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0100'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_vhdlcode<a id="a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0200'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_xml<a id="a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0400'0000'0000ULL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lex_xmlcode<a id="a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000'0800'0000'0000ULL)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7d">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> : uint64_t {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">29</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">Quiet</a>             =             0x00'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Preprocessor</a>      =             0x00'0001ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">CommentCnv</a>        =             0x00'0002ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">CommentScan</a>       =             0x00'0004ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997">Formula</a>           =             0x00'0008ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">PrintTree</a>         =             0x00'0010ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Time</a>              =             0x00'0020ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3">ExtCmd</a>            =             0x00'0040ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Markdown</a>          =             0x00'0080ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">FilterOutput</a>      =             0x00'0100ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Plantuml</a>          =             0x00'0200ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">FortranFixed2Free</a> =             0x00'0400ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da724abc65281c2d47105ebf8a31d6c397">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da724abc65281c2d47105ebf8a31d6c397">Cite</a>              =             0x00'0800ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62">NoLineNo</a>          =             0x00'1000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc">Rtf</a>               =             0x00'2000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dad9460df52aaeff184624ce6b5a5360e2">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dad9460df52aaeff184624ce6b5a5360e2">Qhp</a>               =             0x00'4000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Tag</a>               =             0x00'8000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc">Alias</a>             =             0x01'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dad9c34d45743a5b17700d8c98e1fd010c">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dad9c34d45743a5b17700d8c98e1fd010c">Entries</a>           =             0x02'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da9087db4bb32e89ea9a871a7dd6e69158">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da9087db4bb32e89ea9a871a7dd6e69158">Sections</a>          =             0x04'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550">Stderr</a>            =             0x08'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Layout</a>            =             0x10'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da0c1d42bd6b09e5427669a49f082e823b">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da0c1d42bd6b09e5427669a49f082e823b">Lex</a>               = 0x0000'FFFF'FF00'0000ULL, </span><span class="doxyHighlightComment">// all scanners combined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Lex_code</a>          = 0x0000'0000'0100'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Lex_commentcnv</a>    = 0x0000'0000'0200'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Lex_commentscan</a>   = 0x0000'0000'0400'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Lex_configimpl</a>    = 0x0000'0000'0800'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dabb929f64e4a2c8c41e79fa5bc4d763f3">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dabb929f64e4a2c8c41e79fa5bc4d763f3">Lex_constexp</a>      = 0x0000'0000'1000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da4fb818b908e028c1bc463472e3959dba">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da4fb818b908e028c1bc463472e3959dba">Lex_declinfo</a>      = 0x0000'0000'2000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">Lex_defargs</a>       = 0x0000'0000'4000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Lex_doctokenizer</a>  = 0x0000'0000'8000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dac254e604d7117b1b02b7a35d96f61714">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dac254e604d7117b1b02b7a35d96f61714">Lex_fortrancode</a>   = 0x0000'0001'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Lex_fortranscanner</a>= 0x0000'0002'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Lex_lexcode</a>       = 0x0000'0004'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Lex_lexscanner</a>    = 0x0000'0008'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">Lex_pre</a>           = 0x0000'0010'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da391da68ca9444e86fc0c86e3b45114da">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da391da68ca9444e86fc0c86e3b45114da">Lex_pycode</a>        = 0x0000'0020'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Lex_pyscanner</a>     = 0x0000'0040'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Lex_scanner</a>       = 0x0000'0080'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7da646fb0e06016ef0b89e2c998a2d4f510">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7da646fb0e06016ef0b89e2c998a2d4f510">Lex_sqlcode</a>       = 0x0000'0100'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Lex_vhdlcode</a>      = 0x0000'0200'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Lex_xml</a>           = 0x0000'0400'0000'0000ULL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Lex_xmlcode</a>       = 0x0000'0800'0000'0000ULL</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">                   };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### clearFlag() {#a8b6226d91e39828116b504b94e22b26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::clearFlag (const <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</td>
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



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b6226d91e39828116b504b94e22b26b">122</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8b6226d91e39828116b504b94e22b26b">Debug::clearFlag</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4d585549eed6b188844447b6149c576e">curMask</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a4d585549eed6b188844447b6149c576e">curMask</a> &amp; ~mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7a6a5293009b6fe08ac25a4040350552">devUsage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/statistics/#a681d86ad7e9121de36d517420e135415">Statistics::print</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6fb9dbb3758f88f97192002d3a48bb2d">usage</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>.</p>

</div>
</div>

### elapsedTime() {#accc1a68a6e51b015caee0ab90ddb6e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double Debug::elapsedTime ()</td>
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



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accc1a68a6e51b015caee0ab90ddb6e87">201</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> <a href="#accc1a68a6e51b015caee0ab90ddb6e87">Debug::elapsedTime</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a>.elapsedTimeS();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a> and <a href="/web-doxygen/docs/api/files/src/message-cpp/#aca6c414913e8be769863ed67c1e82141">msg_</a>.</p>

</div>
</div>

### isFlagSet() {#a96e9401783e852c91f341b3f98198061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Debug::isFlagSet (const <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</td>
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



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96e9401783e852c91f341b3f98198061">132</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (<a href="#a4d585549eed6b188844447b6149c576e">curMask</a> &amp; mask)!=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/ccodeparser/#a53fde266eef5df6e4c65286e04fd739c">CCodeParser::CCodeParser</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a4cc03eb4b903175c815dbbe1c9caa027">CommentScanner::CommentScanner</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/classes/coutlineparser/#a5d4323648b52f514ea8c0c71537359a5">COutlineParser::COutlineParser</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a21e0a716a4ba27ef05394fdd16276eec">determineInkscapeVersion</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a6384abe92f96fc6fa9c2fd47ce057b6e">DocTokenizer::DocTokenizer</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#a21fc1ba3570d499b095e5ba8559f287f">FortranCodeParser::FortranCodeParser</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#aef1d730d619e5441ab6206a8fd5b1a45">FormulaManager::generateImages</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/lexcodeparser/#ab888b9484e3ea4ac127f6a4e08a66415">LexCodeParser::LexCodeParser</a>, <a href="/web-doxygen/docs/api/classes/lexoutlineparser/#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser::LexOutlineParser</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#aca6c414913e8be769863ed67c1e82141">msg_</a>, <a href="/web-doxygen/docs/api/classes/constexpressionparser/#af6f5dbdc0aadd6150973487b9c2d7514">ConstExpressionParser::parse</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a772414bc571e725007f1c8bc15ebb355">preProcessFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/classes/debuglex/#aba76b8a3cf651c0fc03dc731a8f880e0">DebugLex::print</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ad6fcec8908014f46c8bb5f69e4bc3b37">print</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>, <a href="/web-doxygen/docs/api/classes/statistics/#a681d86ad7e9121de36d517420e135415">Statistics::print</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a001e5e4b6b99ed83d3333cc3adf5afd2">printNavTree</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a15f08e6d7d71c59e3d83275bbef45ac5">printSectionsTree</a>, <a href="/web-doxygen/docs/api/structs/fortranoutlineparser/private/#a775249ff6240140781b373d7c12de338">FortranOutlineParser::Private::Private</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7104fd0fa8b8761e10dc96c4b053b1f5">PythonCodeParser::PythonCodeParser</a>, <a href="/web-doxygen/docs/api/classes/pythonoutlineparser/#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser::PythonOutlineParser</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91768fc1635556eefd2d96ea1751435d">runHtmlHelpCompiler</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e8f1fbd720c602f867aa536e450462">runQHelpGenerator</a>, <a href="/web-doxygen/docs/api/classes/sqlcodeparser/#adf13c0f853d70fa5244e2acf670a49b9">SQLCodeParser::SQLCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a6c48ab414d705c2bc9c6c7c48cf04b90">VHDLCodeParser::VHDLCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a> and <a href="/web-doxygen/docs/api/classes/xmlcodeparser/#a7b752edfd8cc2c382a7a0289b315f890">XMLCodeParser::XMLCodeParser</a>.</p>

</div>
</div>

### print() {#a970761e07475cafdd9fd5395a0c83544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::print (<a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask, int prio, fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a970761e07475cafdd9fd5395a0c83544">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a970761e07475cafdd9fd5395a0c83544">print</a>(<a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prio,fmt::format_string&lt;Args...&gt; <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af9d002a2d503fa172cc502ccb1198f8c">print_</a>(mask,prio,<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,fmt::make_format_args(args...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#af9d002a2d503fa172cc502ccb1198f8c">print_</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3e6c42b51465b9d08e7e894fe3673b5b">FileDefImpl::acquireFileVersion</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#ad1fa14f7ebd8d6adedcac12a2fb83ae1">addValidAliasToMap</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous{tagreader.cpp}::TagFileParser::dump</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a436ad51276d8a9373fa734742a56fb4f">expandAlias</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#ad313a32a960f39f775ebb6d5bc8c5fe1">FilterCache::getFileContentsPipe</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#aa83ff077c80d8e2dc04a28e1629cff12">PlantumlManager::insert</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#ad6fcec8908014f46c8bb5f69e4bc3b37">print</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#aaa383e6d12f58596fe30c0de9a8d82b1">print</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ad2711841592974bc20e2390475c4c45d">printLayout</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a001e5e4b6b99ed83d3333cc3adf5afd2">printNavTree</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a15f08e6d7d71c59e3d83275bbef45ac5">printSectionsTree</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a6b8eb655dd98d5b700055fc5ae0440dc">resolveAliasCmd</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af38a83e442553a769951c724353cbe6a">PlantumlManager::run</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e8f1fbd720c602f867aa536e450462">runQHelpGenerator</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.</p>

</div>
</div>

### print\_() {#af9d002a2d503fa172cc502ccb1198f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::print_ (<a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask, int prio, fmt::string_view fmt, fmt::format_args args)</td>
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



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9d002a2d503fa172cc502ccb1198f8c">81</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af9d002a2d503fa172cc502ccb1198f8c">Debug::print_</a>(<a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prio, fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a4d585549eed6b188844447b6149c576e">curMask</a>&amp;mask) &amp;&amp; prio&lt;=<a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    fmt::print(<a href="/web-doxygen/docs/api/files/src/debug-cpp/#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a>,</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>, <a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a> and <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a>.</p>


<p>Referenced by <a href="#a970761e07475cafdd9fd5395a0c83544">print</a>.</p>

</div>
</div>

### printFlags() {#a2d8ac411144a380f838a1766118c6a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::printFlags ()</td>
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



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d8ac411144a380f838a1766118c6a03">137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2d8ac411144a380f838a1766118c6a03">Debug::printFlags</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;v : <a href="/web-doxygen/docs/api/files/src/debug-cpp/#ab76040705893c60ac02bcca04c9aba5f">s_labels</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"\t{}\n"</span><span class="doxyHighlight">,v.first);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> and <a href="/web-doxygen/docs/api/files/src/debug-cpp/#ab76040705893c60ac02bcca04c9aba5f">s_labels</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7a6a5293009b6fe08ac25a4040350552">devUsage</a>.</p>

</div>
</div>

### setFlag() {#affb7c17adbcafb5ec252e95c70f12f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::setFlag (const <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</td>
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



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affb7c17adbcafb5ec252e95c70f12f53">117</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#affb7c17adbcafb5ec252e95c70f12f53">Debug::setFlag</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> mask)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4d585549eed6b188844447b6149c576e">curMask</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a4d585549eed6b188844447b6149c576e">curMask</a> | mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a> and <a href="/web-doxygen/docs/api/classes/statistics/#a681d86ad7e9121de36d517420e135415">Statistics::print</a>.</p>

</div>
</div>

### setFlagStr() {#ae37b8f08c49a5d316b436e1849dffb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Debug::setFlagStr (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label)</td>
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



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae37b8f08c49a5d316b436e1849dffb9c">103</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae37b8f08c49a5d316b436e1849dffb9c">Debug::setFlagStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  uint64_t retVal = <a href="/web-doxygen/docs/api/files/src/debug-cpp/#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a>(lab);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retVal == <a href="#a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550">Debug::Stderr</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a> = stderr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4d585549eed6b188844447b6149c576e">curMask</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a4d585549eed6b188844447b6149c576e">curMask</a> | retVal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retVal!=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>, <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a>, <a href="/web-doxygen/docs/api/files/src/debug-cpp/#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a> and <a href="#a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550">Stderr</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.</p>

</div>
</div>

### setPriority() {#a666b610770dd7b7c0a87f2415aefe7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::setPriority (int p)</td>
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



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a666b610770dd7b7c0a87f2415aefe7d9">127</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a666b610770dd7b7c0a87f2415aefe7d9">Debug::setPriority</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a> = p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a>.</p>

</div>
</div>

### startTimer() {#ad34e8ad3d814a4cf8b29ce98fd7a96f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Debug::startTimer ()</td>
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



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>, definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad34e8ad3d814a4cf8b29ce98fd7a96f5">196</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad34e8ad3d814a4cf8b29ce98fd7a96f5">Debug::startTimer</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a>.start();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/debug-cpp/#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a122070be7aebc9e3ab560b58fdd922c9">initDoxygen</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### curMask {#a4d585549eed6b188844447b6149c576e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Debug::DebugMask Debug::curMask = <a href="#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">Debug::Quiet</a></td>
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



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d585549eed6b188844447b6149c576e">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a1c3f4696cf44a23f41e034323c426f7d">DebugMask</a> <a href="#a4d585549eed6b188844447b6149c576e">curMask</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8b6226d91e39828116b504b94e22b26b">clearFlag</a>, <a href="#a96e9401783e852c91f341b3f98198061">isFlagSet</a>, <a href="#af9d002a2d503fa172cc502ccb1198f8c">print_</a>, <a href="#affb7c17adbcafb5ec252e95c70f12f53">setFlag</a> and <a href="#ae37b8f08c49a5d316b436e1849dffb9c">setFlagStr</a>.</p>

</div>
</div>

### curPrio {#a7fef523d45f91d03f5e90469060a3b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Debug::curPrio = 0</td>
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



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fef523d45f91d03f5e90469060a3b97">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7fef523d45f91d03f5e90469060a3b97">curPrio</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af9d002a2d503fa172cc502ccb1198f8c">print_</a> and <a href="#a666b610770dd7b7c0a87f2415aefe7d9">setPriority</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
