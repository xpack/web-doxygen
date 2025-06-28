---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlhelprecoder
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `HtmlHelpRecoder` Class Reference

<p>Helper class to deal with recoding the UTF8 encoded text back to the native encoding specified by CHM_INDEX_ENCODING. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlHelpRecoder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d90fe97c752a21a0806ee6eb5b7c33">HtmlHelpRecoder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70452af4e4bc1ae32830545090d28a18">~HtmlHelpRecoder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8015f456496f1510c8e8643f959376">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cf0d51cc8f1d0cbac630757606f50b">recode</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a> = reinterpret&#95;cast&lt;void&#42;&gt;(-1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a> = <a href="#a6a2a996575156ef3090e22a336bb6058">m&#95;iconv&#95;null</a></td>
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

<p>Helper class to deal with recoding the UTF8 encoded text back to the native encoding specified by CHM_INDEX_ENCODING.</p>

<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### HtmlHelpRecoder() {#aa2d90fe97c752a21a0806ee6eb5b7c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelpRecoder::HtmlHelpRecoder ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2d90fe97c752a21a0806ee6eb5b7c33">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa2d90fe97c752a21a0806ee6eb5b7c33">HtmlHelpRecoder</a>() {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~HtmlHelpRecoder() {#a70452af4e4bc1ae32830545090d28a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelpRecoder::~HtmlHelpRecoder ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70452af4e4bc1ae32830545090d28a18">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a70452af4e4bc1ae32830545090d28a18">~HtmlHelpRecoder</a>() { <a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a>(); }</span></span></div>

</div>


Reference <a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a1a26634d3db023f8cdbe4f19db32ceee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelpRecoder::finalize ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a26634d3db023f8cdbe4f19db32ceee">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a>!=<a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/portable-h/#a3f98144680118aada1a93d2d4ba6173b">portable_iconv_close</a>(<a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a> = <a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a13f3059889c68cfe83674828ab529168">m&#95;fromUtf8</a>, <a href="#a6a2a996575156ef3090e22a336bb6058">m&#95;iconv&#95;null</a> and <a href="/web-doxygen/docs/api/files/src/portable-h/#a3f98144680118aada1a93d2d4ba6173b">portable&#95;iconv&#95;close</a>.

Referenced by <a href="#a70452af4e4bc1ae32830545090d28a18">~HtmlHelpRecoder</a>.
</div>
</div>

### initialize() {#aaf8015f456496f1510c8e8643f959376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelpRecoder::initialize ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf8015f456496f1510c8e8643f959376">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    void <a href="#aaf8015f456496f1510c8e8643f959376">initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> str = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(CHM_INDEX_ENCODING);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) str = </span><span class="doxyHighlightStringLiteral">"CP1250"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// use safe and likely default</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a> = <a href="/web-doxygen/docs/api/files/src/portable-h/#a7bc4daae6d2c3e89837c44e2c3d4dac6">portable_iconv_open</a>(str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a>==<a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"unsupported character conversion for CHM_INDEX_ENCODING: '{}'-&gt;'UTF-8'\n"</span><span class="doxyHighlight">, str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#aaf8015f456496f1510c8e8643f959376">initialize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a13f3059889c68cfe83674828ab529168">m&#95;fromUtf8</a>, <a href="#a6a2a996575156ef3090e22a336bb6058">m&#95;iconv&#95;null</a>, <a href="/web-doxygen/docs/api/files/src/portable-h/#a7bc4daae6d2c3e89837c44e2c3d4dac6">portable&#95;iconv&#95;open</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.

Referenced by <a href="#aaf8015f456496f1510c8e8643f959376">initialize</a>.
</div>
</div>

### recode() {#a54cf0d51cc8f1d0cbac630757606f50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlHelpRecoder::recode (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54cf0d51cc8f1d0cbac630757606f50b">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a54cf0d51cc8f1d0cbac630757606f50b">recode</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> iSize     = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> oSize     = iSize*4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> output(oSize, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> iLeft     = iSize;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> oLeft     = oSize;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *iPtr = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *oPtr       = output.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/portable-h/#a5fc5ec1eedfa06b27448863f69ee2e1d">portable_iconv</a>(<a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a>,&amp;iPtr,&amp;iLeft,&amp;oPtr,&amp;oLeft))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">        oSize -= oLeft;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">        output.<a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">resize</a>(oSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">        output.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(oSize)=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> output;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a13f3059889c68cfe83674828ab529168">m&#95;fromUtf8</a>, <a href="/web-doxygen/docs/api/files/src/portable-h/#a5fc5ec1eedfa06b27448863f69ee2e1d">portable&#95;iconv</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">QCString::resize</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;fromUtf8 {#a13f3059889c68cfe83674828ab529168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* HtmlHelpRecoder::m_fromUtf8 = <a href="#a6a2a996575156ef3090e22a336bb6058">m&#95;iconv&#95;null</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00091">91</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13f3059889c68cfe83674828ab529168">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *<a href="#a13f3059889c68cfe83674828ab529168">m_fromUtf8</a> = <a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a>;</span></span></div>

</div>


Referenced by <a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a>, <a href="#aaf8015f456496f1510c8e8643f959376">initialize</a> and <a href="#a54cf0d51cc8f1d0cbac630757606f50b">recode</a>.
</div>
</div>

### m&#95;iconv&#95;null {#a6a2a996575156ef3090e22a336bb6058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* HtmlHelpRecoder::m_iconv_null = reinterpret&#95;cast&lt;void&#42;&gt;(-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#l00090">90</a> of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a2a996575156ef3090e22a336bb6058">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *<a href="#a6a2a996575156ef3090e22a336bb6058">m_iconv_null</a> = </span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(-1);</span></span></div>

</div>


Referenced by <a href="#a1a26634d3db023f8cdbe4f19db32ceee">finalize</a> and <a href="#aaf8015f456496f1510c8e8643f959376">initialize</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
