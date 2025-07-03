---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/portable-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `portable.h` File Reference

<p><a href="/web-doxygen/docs/api/namespaces/portable">Portable</a> versions of functions that are platform dependent. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;sys/types.h&gt;
#include &lt;stdint.h&gt;
#include &lt;fstream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/portable">Portable</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc4daae6d2c3e89837c44e2c3d4dac6">portable_iconv_open</a> (const char *tocode, const char *fromcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc5ec1eedfa06b27448863f69ee2e1d">portable_iconv</a> (void *cd, const char **inbuf, size_t *inbytesleft, char **outbuf, size_t *outbytesleft)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f98144680118aada1a93d2d4ba6173b">portable_iconv_close</a> (void *cd)</td>
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

<p><a href="/web-doxygen/docs/api/namespaces/portable">Portable</a> versions of functions that are platform dependent.</p>

<div class="doxySectionDef">

## Functions

### portable\_iconv() {#a5fc5ec1eedfa06b27448863f69ee2e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t portable_iconv (void * cd, const char ** inbuf, size_t * inbytesleft, char ** outbuf, size_t * outbytesleft)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a54cf0d51cc8f1d0cbac630757606f50b">HtmlHelpRecoder::recode</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.</p>

</div>
</div>

### portable\_iconv\_close() {#a3f98144680118aada1a93d2d4ba6173b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int portable_iconv_close (void * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#a1a26634d3db023f8cdbe4f19db32ceee">HtmlHelpRecoder::finalize</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.</p>

</div>
</div>

### portable\_iconv\_open() {#a7bc4daae6d2c3e89837c44e2c3d4dac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * portable_iconv_open (const char * tocode, const char * fromcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlhelprecoder/#aaf8015f456496f1510c8e8643f959376">HtmlHelpRecoder::initialize</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a724f5508f1314342da28cc51b867431b">Portable::recodeUtf8StringToW</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
