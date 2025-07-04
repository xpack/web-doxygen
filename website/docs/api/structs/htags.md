---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/htags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Htags` Struct Reference

<p>This class is a namespace for HTAGS related functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct Htags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htags-h">src/htags.h</a>&gt;
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a5a1322fbff8f8ad136a3372964512">loadFilemap</a> (const QCString &amp;htmldir)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce955dfddd8473bce6373e92532f12e">path2URL</a> (const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a459ba4c5a4e6d3308cee25b93448f0cf">execute</a> (const QCString &amp;htmldir)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f32647c4c570264405de97f51cad05">useHtags</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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

<p>This class is a namespace for HTAGS related functions.</p>

<p>Definition at line 21 of file <a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### execute() {#a459ba4c5a4e6d3308cee25b93448f0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Htags::execute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; htmldir)</td>
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




<p>constructs command line of htags(1) and executes it.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Return Values</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TRUE</td>
<td class="doxyParamItemDescription"><p>success</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FALSE</td>
<td class="doxyParamItemDescription"><p>an error has occurred.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 26 of file <a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>, definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a459ba4c5a4e6d3308cee25b93448f0cf">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a459ba4c5a4e6d3308cee25b93448f0cf">Htags::execute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;htmldir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;inputSource = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(INPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> quiet = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> warnings = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARNINGS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> htagsOptions = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//Config_getString(HTAGS_OPTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectNumber = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NUMBER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputSource.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>.setPath(<a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputSource.size()==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>.setPath(inputSource.back());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>.exists())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot find directory {}. "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Check the value of the INPUT tag in the configuration file.\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">          inputSource.back()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">         );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"If you use USE_HTAGS then INPUT should specify a single directory.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * Construct command line for htags(1).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlightComment">   */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> commandLine = </span><span class="doxyHighlightStringLiteral">" -g -s -a -n "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!quiet)   commandLine += </span><span class="doxyHighlightStringLiteral">"-v "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (warnings) commandLine += </span><span class="doxyHighlightStringLiteral">"-w "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!htagsOptions.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    commandLine += </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    commandLine += htagsOptions;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!projectName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    commandLine += </span><span class="doxyHighlightStringLiteral">"-t \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    commandLine += projectName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!projectNumber.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      commandLine += </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      commandLine += projectNumber;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    commandLine += </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  commandLine += </span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight"> + htmldir + </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string oldDir = <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a>(<a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>.absPath());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("CommandLine=[%s]\n",qPrint(commandLine));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> result=<a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>(</span><span class="doxyHighlightStringLiteral">"htags"</span><span class="doxyHighlight">,commandLine,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)==0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Problems running htags. Check your installation\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a>(oldDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

### loadFilemap() {#a91a5a1322fbff8f8ad136a3372964512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Htags::loadFilemap (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; htmlDir)</td>
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




<p>load filemap and make index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">htmlDir</td>
<td class="doxyParamItemDescription"><p>of HTML directory generated by htags(1).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Return Values</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TRUE</td>
<td class="doxyParamItemDescription"><p>success</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FALSE</td>
<td class="doxyParamItemDescription"><p>error</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 24 of file <a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>, definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91a5a1322fbff8f8ad136a3372964512">107</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;htmlDir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileMapName = htmlDir+</span><span class="doxyHighlightStringLiteral">"/HTML/FILEMAP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileMapName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * Construct FILEMAP dictionary.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * In FILEMAP, URL includes 'html' suffix but we cut it off according</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * to the method of FileDef class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * FILEMAP format:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * &lt;NAME&gt;\t&lt;HREF&gt;.html\n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * QDICT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * dict[&lt;NAME&gt;] = &lt;HREF&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlightComment">   */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">isReadable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ifstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(fileMapName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string lineStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (getline(f,lineStr))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> line(lineStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Read line: %s",qPrint(line));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sep = line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sep!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> key   = line.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(sep).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> value = line.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(sep+1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ext=value.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ext!=-1) value=value.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(ext); </span><span class="doxyHighlightComment">// strip extension</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>.emplace(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),value.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("Key/Value=(%s,%s)\n",qPrint(key),qPrint(value));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"file {} cannot be opened\n"</span><span class="doxyHighlight">,fileMapName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">FileInfo::isReadable</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

### path2URL() {#a0ce955dfddd8473bce6373e92532f12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Htags::path2URL (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
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




<p>convert path name into the url in the hypertext generated by htags.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>path name</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>URL nullptr: not found.</p></dd>
</dl>


<p>Declaration at line 25 of file <a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>, definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ce955dfddd8473bce6373e92532f12e">157</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url,symName=path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dir = <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>.absPath();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> dl=dir.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (symName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;dl+1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    symName = symName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(dl+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!symName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>.find(symName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("path2URL=%s symName=%s result=%p\n",qPrint(path),qPrint(symName),result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/htags-cpp/#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      url = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"HTML/"</span><span class="doxyHighlight">+it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>, <a href="/web-doxygen/docs/api/files/src/htags-cpp/#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a4d119855709ae055bf544d312529599c">FileDefImpl::getSourceFileBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### useHtags {#af3f32647c4c570264405de97f51cad05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Htags::useHtags = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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



<p>Definition at line 23 of file <a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3f32647c4c570264405de97f51cad05">23</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af3f32647c4c570264405de97f51cad05">useHtags</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a8d97a542b3b830868e0cdc39aac6c98c">DefinitionImpl::getSourceAnchor</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a4d119855709ae055bf544d312529599c">FileDefImpl::getSourceFileBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
