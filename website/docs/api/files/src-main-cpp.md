---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/main-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `main.cpp` File Reference

<p>main entry point for doxygen <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c04138a5bfe5d72780bb7e82a18e627">main</a> (int argc, char **argv)</td>
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

<p>main entry point for doxygen</p>


<p>This file contains <a href="#a3c04138a5bfe5d72780bb7e82a18e627">main()</a></p>


<div class="doxySectionDef">

## Functions

### main() {#a3c04138a5bfe5d72780bb7e82a18e627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int main (int argc, char ** argv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Default main. The idea of separating this from the rest of doxygen, is to make it possible to write your own main, with a different <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput()</a> function for instance.</p>


<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/main-cpp">main.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c04138a5bfe5d72780bb7e82a18e627">31</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3c04138a5bfe5d72780bb7e82a18e627">main</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> argc,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> **argv)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a122070be7aebc9e3ab560b58fdd922c9">initDoxygen</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>(argc,argv);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a122070be7aebc9e3ab560b58fdd922c9">initDoxygen</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
