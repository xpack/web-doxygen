---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/spanishtranslatorutils
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `SpanishTranslatorUtils` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace SpanishTranslatorUtils { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0a58a993242ebe35f353df83ac3dfc">isClassMemberHighlightMasculine</a> (ClassMemberHighlight::Enum hl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb2ec9f1537ce74a8bedb39541aed6f">isFileMemberHighlightMasculine</a> (FileMemberHighlight::Enum hl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bcfe6cfbe005860a4966f5920567c81">isNamespaceMemberHighlightMasculine</a> (NamespaceMemberHighlight::Enum hl)</td>
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



<a href="/web-doxygen/docs/api/files/src/translator-es-h">translator\_es.h</a> modified by Lucas Cruz (7-julio-2000) Updated from 1.3.8 to 1.4.6 by Guillermo Ballester Valor (May-05-2006) Updated to 1.5.1 by Bartomeu Creus Navarro (22-enero-2007) Updated to 1.5.5 by Bartomeu Creus Navarro (5-febrero-2008) Updated to 1.5.8 by Bartomeu Creus Navarro (10-abril-2009) Updated to 1.6.3 by Bartomeu Creus Navarro (3-marzo-2010) Updated to 1.6.4 by Bartomeu Creus Navarro (26-mayo-2010) \[(16-jun-2010) grabado en UTF-8\] Updated to 1.8.0 by Bartomeu Creus Navarro (11-abril-2012) Updated to 1.8.2 by Bartomeu Creus Navarro (01-julio-2012) Updated to 1.8.4 by Bartomeu Creus Navarro (17-julio-2013) Updated to 1.9.6 by David H. Martín (28-diciembre-2022) Updated to 1.9.7 by David H. Martín (27-marzo-2023)

<div class="doxySectionDef">

## Functions

### isClassMemberHighlightMasculine() {#a2f0a58a993242ebe35f353df83ac3dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpanishTranslatorUtils::isClassMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beb">ClassMemberHighlight::Enum</a> hl)</td>
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




Returns true if the gender of the given component is masculine in Spanish.

Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/translator-es-h">translator_es.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f0a58a993242ebe35f353df83ac3dfc">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2f0a58a993242ebe35f353df83ac3dfc">isClassMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beb">ClassMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_FOR_C))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// structs and unions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// class members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebace63d3b887ff69dc23d3bcf921399f04">ClassMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba19d9a8f4e05df2e1a3475c55060fac6b">ClassMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba7046101c6dcadf2e24d1957e9f239554">ClassMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba5ddbeed21dbb7628f833e7e6d8119cb6">ClassMemberHighlight::Properties</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba373da1884065adefbae311305eb2db9b">ClassMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba3032b799b82514421a73aa3c41963261">ClassMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebad729fb1b23106e5472bec39ff0e8fa75">ClassMemberHighlight::Events</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba414351f516224ef9dc574636365547d1">ClassMemberHighlight::Related</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba7046101c6dcadf2e24d1957e9f239554">ClassMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba373da1884065adefbae311305eb2db9b">ClassMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebad729fb1b23106e5472bec39ff0e8fa75">ClassMemberHighlight::Events</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5bebace63d3b887ff69dc23d3bcf921399f04">ClassMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba5ddbeed21dbb7628f833e7e6d8119cb6">ClassMemberHighlight::Properties</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba414351f516224ef9dc574636365547d1">ClassMemberHighlight::Related</a>, <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba3032b799b82514421a73aa3c41963261">ClassMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba19d9a8f4e05df2e1a3475c55060fac6b">ClassMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorspanish/#a56039721e29b76d5fa8d9f892cff0bbc">TranslatorSpanish::trCompoundMembersDescriptionTotal</a>.
</div>
</div>

### isFileMemberHighlightMasculine() {#a0cb2ec9f1537ce74a8bedb39541aed6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpanishTranslatorUtils::isFileMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550">FileMemberHighlight::Enum</a> hl)</td>
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




Returns true if the gender of the given component is masculine in Spanish.

Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/translator-es-h">translator_es.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cb2ec9f1537ce74a8bedb39541aed6f">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0cb2ec9f1537ce74a8bedb39541aed6f">isFileMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550">FileMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_FOR_C))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// functions, variables...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// file members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a55566e280dbc48c59582757eeffb0c66">FileMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a8f2dc989544bd5a25930094ce51c05a3">FileMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a6dd12687d93e22e14a20d351f9f3d74c">FileMemberHighlight::Sequences</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a0a64469e670acdb15c0e54f163442f23">FileMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a59883aafd8f0fe50292a1c0b1e76a193">FileMemberHighlight::Defines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a7aca50dbdbeebcccc32785478c9839b2">FileMemberHighlight::Dictionaries</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a848a73782770c7b91561c70630dc2616">FileMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550abb544fc0cd4889c5c428c9dfe186b4cb">FileMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a59883aafd8f0fe50292a1c0b1e76a193">FileMemberHighlight::Defines</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a7aca50dbdbeebcccc32785478c9839b2">FileMemberHighlight::Dictionaries</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a0a64469e670acdb15c0e54f163442f23">FileMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a848a73782770c7b91561c70630dc2616">FileMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a55566e280dbc48c59582757eeffb0c66">FileMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a6dd12687d93e22e14a20d351f9f3d74c">FileMemberHighlight::Sequences</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550abb544fc0cd4889c5c428c9dfe186b4cb">FileMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a8f2dc989544bd5a25930094ce51c05a3">FileMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorspanish/#a48545d5f7c7fd74bed6dfba9e51c0b0f">TranslatorSpanish::trFileMembersDescriptionTotal</a>.
</div>
</div>

### isNamespaceMemberHighlightMasculine() {#a8bcfe6cfbe005860a4966f5920567c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpanishTranslatorUtils::isNamespaceMemberHighlightMasculine (<a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7c">NamespaceMemberHighlight::Enum</a> hl)</td>
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




Returns true if the gender of the given component is masculine in Spanish.

Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/translator-es-h">translator_es.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8bcfe6cfbe005860a4966f5920567c81">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8bcfe6cfbe005860a4966f5920567c81">isNamespaceMemberHighlightMasculine</a>(<a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7c">NamespaceMemberHighlight::Enum</a> hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca69da3a4829e3330851f4ca6d2828018f">NamespaceMemberHighlight::Functions</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca653b486e14d3775eff75c1fc3582557a">NamespaceMemberHighlight::Variables</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca612a9d9df61450edc5503a6bf328b3b1">NamespaceMemberHighlight::Sequences</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca3c3fda61a1823a23e8c49f3c915859f3">NamespaceMemberHighlight::Enums</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca058990972fd9b9f273438f613c9599c5">NamespaceMemberHighlight::Dictionaries</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca2c419cf729051a9e2eef2743ccc9f84d">NamespaceMemberHighlight::EnumValues</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca600a97f79b076618a0891f10352c0fdb">NamespaceMemberHighlight::Typedefs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca058990972fd9b9f273438f613c9599c5">NamespaceMemberHighlight::Dictionaries</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca3c3fda61a1823a23e8c49f3c915859f3">NamespaceMemberHighlight::Enums</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca2c419cf729051a9e2eef2743ccc9f84d">NamespaceMemberHighlight::EnumValues</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca69da3a4829e3330851f4ca6d2828018f">NamespaceMemberHighlight::Functions</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca612a9d9df61450edc5503a6bf328b3b1">NamespaceMemberHighlight::Sequences</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca600a97f79b076618a0891f10352c0fdb">NamespaceMemberHighlight::Typedefs</a> and <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca653b486e14d3775eff75c1fc3582557a">NamespaceMemberHighlight::Variables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorspanish/#a3bae1ebb5930767ed2f85f3d64bf0bb7">TranslatorSpanish::trNamespaceMembersDescriptionTotal</a>.
</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/translator-es-h">translator_es.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
