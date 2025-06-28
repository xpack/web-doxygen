---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/resourcemgr
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ResourceMgr` Class Reference

<p>Singleton for managing resources compiled into an executable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ResourceMgr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/resourcemgr-h">src/resourcemgr.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9daad2dabbe144b6c7f8cdf0d25568b">~ResourceMgr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f39af9986eadf7af87bdc52e607f0e">registerResources</a> (std::initializer_list&lt; Resource &gt; resources)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers an array of resources. <a href="#af1f39af9986eadf7af87bdc52e607f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d65000b297d313a09e4c1cca1f17e0">writeCategory</a> (const QCString &amp;categoryName, const QCString &amp;targetDir) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes all resource belonging to a given category to a given target directory. <a href="#a64d65000b297d313a09e4c1cca1f17e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b8297da656a43a255a3a1b27c210b9">copyResource</a> (const QCString &amp;name, const QCString &amp;targetDir) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies a registered resource to a given target directory. <a href="#a32b8297da656a43a255a3a1b27c210b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad396917a059d354b1ff240b9af3a006c">copyResourceAs</a> (const QCString &amp;name, const QCString &amp;targetDir, const QCString &amp;targetName, bool append=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies a registered resource to a given target directory under a given target name. <a href="#ad396917a059d354b1ff240b9af3a006c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60ef164e79a11cfa31de29221db11aa">getAsString</a> (const QCString &amp;name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the resource data as a C string. <a href="#aa60ef164e79a11cfa31de29221db11aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/resource">Resource</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc16163bd7e09f324093b641113b077">get</a> (const QCString &amp;name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the resource object with the given name. <a href="#a2bc16163bd7e09f324093b641113b077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/resourcemgr/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02fb3176893696eaf659d680c8b08064">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the one and only instance of this class. <a href="#a02fb3176893696eaf659d680c8b08064">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Singleton for managing resources compiled into an executable.</p>

<p>Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>.</p>

<div class="doxySectionDef">

## Private Constructors

### ResourceMgr() {#add6ae734009ee107cd2b644fe6fbb39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceMgr::ResourceMgr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add6ae734009ee107cd2b644fe6fbb39a">39</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr::ResourceMgr</a>() : <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/resourcemgr/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>.

Referenced by <a href="#a02fb3176893696eaf659d680c8b08064">instance</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### ~ResourceMgr() {#af9daad2dabbe144b6c7f8cdf0d25568b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceMgr::~ResourceMgr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9daad2dabbe144b6c7f8cdf0d25568b">43</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af9daad2dabbe144b6c7f8cdf0d25568b">ResourceMgr::~ResourceMgr</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyResource() {#a32b8297da656a43a255a3a1b27c210b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceMgr::copyResource (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; targetDir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Copies a registered resource to a given target directory.</p>

<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32b8297da656a43a255a3a1b27c210b9">122</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a32b8297da656a43a255a3a1b27c210b9">ResourceMgr::copyResource</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;targetDir)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad396917a059d354b1ff240b9af3a006c">copyResourceAs</a>(name,targetDir,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ad396917a059d354b1ff240b9af3a006c">copyResourceAs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7306ef9abbceafd6074b4d883a59f033">HtmlGenerator::writeTabData</a>.
</div>
</div>

### copyResourceAs() {#ad396917a059d354b1ff240b9af3a006c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceMgr::copyResourceAs (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; targetDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; targetName, bool append=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Copies a registered resource to a given target directory under a given target name.</p>

<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad396917a059d354b1ff240b9af3a006c">79</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad396917a059d354b1ff240b9af3a006c">ResourceMgr::copyResourceAs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;targetDir,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;targetName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> append)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pathName = targetDir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+targetName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/resource">Resource</a> *res = <a href="#a2bc16163bd7e09f324093b641113b077">get</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#ae73282ad08d3c990c8a0ff353e231ab3">type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/resource/#abde5e686869a8c7241557d18033b382eaf197aa4cab57b5ab94f906de74015e27">Resource::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">          std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(pathName,append);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">            f.write(</span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#ac5775d3448fb9ed16c0ec90dbed87a71">data</a>),res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">size</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">            ok = !f.fail();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/resource/#abde5e686869a8c7241557d18033b382eabb7175dffd36169ed5e9dedf6e508bdf">Resource::SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">          std::ofstream t = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(pathName,append);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> buf(res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">            memcpy(buf.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>(),res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#ac5775d3448fb9ed16c0ec90dbed87a71">data</a>,res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">size</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(buf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"requested resource '{}' not compiled in!\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/resource/#ac5775d3448fb9ed16c0ec90dbed87a71">Resource::data</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a2bc16163bd7e09f324093b641113b077">get</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">Resource::size</a>, <a href="/web-doxygen/docs/api/structs/resource/#abde5e686869a8c7241557d18033b382eabb7175dffd36169ed5e9dedf6e508bdf">Resource::SVG</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/resource/#ae73282ad08d3c990c8a0ff353e231ab3">Resource::type</a> and <a href="/web-doxygen/docs/api/structs/resource/#abde5e686869a8c7241557d18033b382eaf197aa4cab57b5ab94f906de74015e27">Resource::Verbatim</a>.

Referenced by <a href="#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>.
</div>
</div>

### getAsString() {#aa60ef164e79a11cfa31de29221db11aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ResourceMgr::getAsString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Gets the resource data as a C string.</p>

<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa60ef164e79a11cfa31de29221db11aa">134</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/resource">Resource</a> *res = <a href="#a2bc16163bd7e09f324093b641113b077">get</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result(res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    memcpy(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>(),res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#ac5775d3448fb9ed16c0ec90dbed87a71">data</a>,res-&gt;<a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">size</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/resource/#ac5775d3448fb9ed16c0ec90dbed87a71">Resource::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="#a2bc16163bd7e09f324093b641113b077">get</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a> and <a href="/web-doxygen/docs/api/structs/resource/#a0f8739be95e0d934239663ea7551060b">Resource::size</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3874b75d86f996ce7d7ca32bea785c56">HtmlGenerator::getNavTreeCss</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6c1132096e93e030970694a61ea6c65f">HtmlGenerator::writeFooterFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a541f0867d38638ee1d3c7611e3d04029">LatexGenerator::writeFooterFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab00e0c98e1c833ae27198d1e10c9c22e">HtmlGenerator::writeHeaderFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ada1c307f5625a7d4b90fc3e1b9ce4da5">LatexGenerator::writeHeaderFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9114c68d96141e80c08efdd497fc010e">HtmlGenerator::writeSearchData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae8f3ee4ac698d6d86e7dcaeebfe04fc9">LatexGenerator::writeStyleInfo</a>.
</div>
</div>

### registerResources() {#af1f39af9986eadf7af87bdc52e607f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceMgr::registerResources (std::initializer_list&lt; <a href="/web-doxygen/docs/api/structs/resource">Resource</a> &gt; resources)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Registers an array of resources.</p>

<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1f39af9986eadf7af87bdc52e607f0e">47</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af1f39af9986eadf7af87bdc52e607f0e">ResourceMgr::registerResources</a>(std::initializer_list&lt;Resource&gt; resources)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;res : resources)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>-&gt;resources.emplace(res.name,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>.
</div>
</div>

### writeCategory() {#a64d65000b297d313a09e4c1cca1f17e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceMgr::writeCategory (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; categoryName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; targetDir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Writes all resource belonging to a given category to a given target directory.</p>

<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64d65000b297d313a09e4c1cca1f17e0">55</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a64d65000b297d313a09e4c1cca1f17e0">ResourceMgr::writeCategory</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;categoryName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;targetDir)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,res] : <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>-&gt;resources)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res.category==categoryName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pathName = targetDir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+res.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(pathName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">        f.write(</span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(res.data),res.size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">        ok = !f.fail();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to write resource '{}' to directory '{}'\n"</span><span class="doxyHighlight">,res.name,targetDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### get() {#a2bc16163bd7e09f324093b641113b077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Resource * ResourceMgr::get (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns a pointer to the resource object with the given name.</p>

<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2bc16163bd7e09f324093b641113b077">127</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/resource">Resource</a> *<a href="#a2bc16163bd7e09f324093b641113b077">ResourceMgr::get</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>-&gt;resources.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>-&gt;resources.end()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#ad396917a059d354b1ff240b9af3a006c">copyResourceAs</a> and <a href="#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aeef2c9c2c3f080afd3ec70e6084b0af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; ResourceMgr::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aeef2c9c2c3f080afd3ec70e6084b0af8">p</a>;</span></span></div>

</div>


Referenced by <a href="#a2bc16163bd7e09f324093b641113b077">get</a>, <a href="#af1f39af9986eadf7af87bdc52e607f0e">registerResources</a>, <a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr</a> and <a href="#a64d65000b297d313a09e4c1cca1f17e0">writeCategory</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a02fb3176893696eaf659d680c8b08064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceMgr &amp; ResourceMgr::instance ()</td>
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
<p>Returns the one and only instance of this class.</p>

<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>, definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02fb3176893696eaf659d680c8b08064">33</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr</a> &amp;<a href="#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr</a> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#add6ae734009ee107cd2b644fe6fbb39a">ResourceMgr</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3874b75d86f996ce7d7ca32bea785c56">HtmlGenerator::getNavTreeCss</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6c1132096e93e030970694a61ea6c65f">HtmlGenerator::writeFooterFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a541f0867d38638ee1d3c7611e3d04029">LatexGenerator::writeFooterFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab00e0c98e1c833ae27198d1e10c9c22e">HtmlGenerator::writeHeaderFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ada1c307f5625a7d4b90fc3e1b9ce4da5">LatexGenerator::writeHeaderFile</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#ae8e105816d60cf56b75c2d13f9d85048">writeJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9114c68d96141e80c08efdd497fc010e">HtmlGenerator::writeSearchData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae8f3ee4ac698d6d86e7dcaeebfe04fc9">LatexGenerator::writeStyleInfo</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7306ef9abbceafd6074b4d883a59f033">HtmlGenerator::writeTabData</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/resourcemgr-cpp">resourcemgr.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
