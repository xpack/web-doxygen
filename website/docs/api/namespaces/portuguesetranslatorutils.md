---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/portuguesetranslatorutils
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `PortugueseTranslatorUtils` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace PortugueseTranslatorUtils { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81439ef1e5570b8ba0fc50f4819f43ba">isClassMemberHighlightMasculine</a> (ClassMemberHighlight::Enum hl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5299ba7903c9a3401dc7335f5f3ac57">isFileMemberHighlightMasculine</a> (FileMemberHighlight::Enum hl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813edc55b09a4390e262ac196a2ae756">isNamespaceMemberHighlightMasculine</a> (NamespaceMemberHighlight::Enum hl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bf9d432c31c6a3c8053ca894545baf">isModuleMemberHighlightMasculine</a> (ModuleMemberHighlight::Enum hl)</td>
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


<div class="doxySectionDef">

## Functions

### isClassMemberHighlightMasculine() {#a81439ef1e5570b8ba0fc50f4819f43ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PortugueseTranslatorUtils::isClassMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beb">ClassMemberHighlight::Enum</a> hl)</td>
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



<p>Returns true if the gender of the given component is masculine in Portuguese.</p>

<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/translator-br-h">translator_br.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81439ef1e5570b8ba0fc50f4819f43ba">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a81439ef1e5570b8ba0fc50f4819f43ba">isClassMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beb">ClassMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_FOR_C))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// as estruturas e uniões</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// os membros da classe</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebace63d3b887ff69dc23d3bcf921399f04">ClassMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba19d9a8f4e05df2e1a3475c55060fac6b">ClassMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba7046101c6dcadf2e24d1957e9f239554">ClassMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba5ddbeed21dbb7628f833e7e6d8119cb6">ClassMemberHighlight::Properties</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba3032b799b82514421a73aa3c41963261">ClassMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba373da1884065adefbae311305eb2db9b">ClassMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebad729fb1b23106e5472bec39ff0e8fa75">ClassMemberHighlight::Events</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba414351f516224ef9dc574636365547d1">ClassMemberHighlight::Related</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba7046101c6dcadf2e24d1957e9f239554">ClassMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba373da1884065adefbae311305eb2db9b">ClassMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebad729fb1b23106e5472bec39ff0e8fa75">ClassMemberHighlight::Events</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebace63d3b887ff69dc23d3bcf921399f04">ClassMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba5ddbeed21dbb7628f833e7e6d8119cb6">ClassMemberHighlight::Properties</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba414351f516224ef9dc574636365547d1">ClassMemberHighlight::Related</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba3032b799b82514421a73aa3c41963261">ClassMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba19d9a8f4e05df2e1a3475c55060fac6b">ClassMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a8b33bb212cfc7cd14fb63d3e94a61c07">TranslatorBrazilian::trCompoundMembersDescriptionTotal</a> and <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a2150e491d4124a0b73f7b28be18c20b0">TranslatorPortuguese::trCompoundMembersDescriptionTotal</a>.
</div>
</div>

### isFileMemberHighlightMasculine() {#ab5299ba7903c9a3401dc7335f5f3ac57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PortugueseTranslatorUtils::isFileMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550">FileMemberHighlight::Enum</a> hl)</td>
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



<p>Returns true if the gender of the given component is masculine in Portuguese.</p>

<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/translator-br-h">translator_br.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5299ba7903c9a3401dc7335f5f3ac57">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab5299ba7903c9a3401dc7335f5f3ac57">isFileMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550">FileMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a7aca50dbdbeebcccc32785478c9839b2">FileMemberHighlight::Dictionaries</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a848a73782770c7b91561c70630dc2616">FileMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a55566e280dbc48c59582757eeffb0c66">FileMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a8f2dc989544bd5a25930094ce51c05a3">FileMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550abb544fc0cd4889c5c428c9dfe186b4cb">FileMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a6dd12687d93e22e14a20d351f9f3d74c">FileMemberHighlight::Sequences</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a0a64469e670acdb15c0e54f163442f23">FileMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a59883aafd8f0fe50292a1c0b1e76a193">FileMemberHighlight::Defines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a59883aafd8f0fe50292a1c0b1e76a193">FileMemberHighlight::Defines</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a7aca50dbdbeebcccc32785478c9839b2">FileMemberHighlight::Dictionaries</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a0a64469e670acdb15c0e54f163442f23">FileMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a848a73782770c7b91561c70630dc2616">FileMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a55566e280dbc48c59582757eeffb0c66">FileMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a6dd12687d93e22e14a20d351f9f3d74c">FileMemberHighlight::Sequences</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550abb544fc0cd4889c5c428c9dfe186b4cb">FileMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a8f2dc989544bd5a25930094ce51c05a3">FileMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a9a15fb5b40047fe6796592a2c1e62a9b">TranslatorBrazilian::trFileMembersDescriptionTotal</a> and <a href="/web-doxygen/docs/api/classes/translatorportuguese/#ad37d9cd1d84455c4625f54647006cd99">TranslatorPortuguese::trFileMembersDescriptionTotal</a>.
</div>
</div>

### isModuleMemberHighlightMasculine() {#ae0bf9d432c31c6a3c8053ca894545baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PortugueseTranslatorUtils::isModuleMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12">ModuleMemberHighlight::Enum</a> hl)</td>
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



<p>Returns true if the gender of the given component is masculine in Brazilian Portuguese and European Portuguese.</p>

<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/translator-br-h">translator_br.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0bf9d432c31c6a3c8053ca894545baf">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae0bf9d432c31c6a3c8053ca894545baf">isModuleMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12">ModuleMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12ac42c0d575d3dc42c53935916d9a23866">ModuleMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a9af17a0ccbd1454a93a60c25fe6004a1">ModuleMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a8b515055e6091c5954d67e42309c33d2">ModuleMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a41bc55ae426fc418c6fb7189d7b2f67e">ModuleMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12afdaf0271b54849b06fb42792c1d8660c">ModuleMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12af7d95aa83835ec0e82a51ba997dde106">ModuleMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12ac42c0d575d3dc42c53935916d9a23866">ModuleMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12af7d95aa83835ec0e82a51ba997dde106">ModuleMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a9af17a0ccbd1454a93a60c25fe6004a1">ModuleMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a8b515055e6091c5954d67e42309c33d2">ModuleMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12afdaf0271b54849b06fb42792c1d8660c">ModuleMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12a41bc55ae426fc418c6fb7189d7b2f67e">ModuleMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#a67d1a2718cdc469a31be735783e3702b">TranslatorBrazilian::trModuleMembersDescriptionTotal</a> and <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a9c123c487354d1da4ce2ac45063b37ca">TranslatorPortuguese::trModuleMembersDescriptionTotal</a>.
</div>
</div>

### isNamespaceMemberHighlightMasculine() {#a813edc55b09a4390e262ac196a2ae756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PortugueseTranslatorUtils::isNamespaceMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7c">NamespaceMemberHighlight::Enum</a> hl)</td>
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



<p>Returns true if the gender of the given component is masculine in Brazilian Portuguese and European Portuguese.</p>

<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/translator-br-h">translator_br.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a813edc55b09a4390e262ac196a2ae756">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a813edc55b09a4390e262ac196a2ae756">isNamespaceMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7c">NamespaceMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca058990972fd9b9f273438f613c9599c5">NamespaceMemberHighlight::Dictionaries</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca2c419cf729051a9e2eef2743ccc9f84d">NamespaceMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca69da3a4829e3330851f4ca6d2828018f">NamespaceMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca653b486e14d3775eff75c1fc3582557a">NamespaceMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca600a97f79b076618a0891f10352c0fdb">NamespaceMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca612a9d9df61450edc5503a6bf328b3b1">NamespaceMemberHighlight::Sequences</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca3c3fda61a1823a23e8c49f3c915859f3">NamespaceMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca058990972fd9b9f273438f613c9599c5">NamespaceMemberHighlight::Dictionaries</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca3c3fda61a1823a23e8c49f3c915859f3">NamespaceMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca2c419cf729051a9e2eef2743ccc9f84d">NamespaceMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca69da3a4829e3330851f4ca6d2828018f">NamespaceMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca612a9d9df61450edc5503a6bf328b3b1">NamespaceMemberHighlight::Sequences</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca600a97f79b076618a0891f10352c0fdb">NamespaceMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca653b486e14d3775eff75c1fc3582557a">NamespaceMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorbrazilian/#ae1d5221621a7b488452448dd357954ab">TranslatorBrazilian::trNamespaceMembersDescriptionTotal</a> and <a href="/web-doxygen/docs/api/classes/translatorportuguese/#a7999fe3e30ba54722fed6e7c5d0d8e01">TranslatorPortuguese::trNamespaceMembersDescriptionTotal</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this namespace was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/translator-br-h">translator_br.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
