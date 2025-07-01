---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/docnode-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `docnode.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/configoptions-h">configoptions.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cmdmapper-h">cmdmapper.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/datetime-h">datetime.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/aliases-h">aliases.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/activerowspan">ActiveRowSpan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Helper class to compute the grid for an HTML style table. <a href="/web-doxygen/docs/api/structs/activerowspan/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/activerowspan">ActiveRowSpan</a> &gt; <a href="#a8ebd411a505f41da49085559bdc9685e">RowSpanList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
List of <a href="/web-doxygen/docs/api/structs/activerowspan">ActiveRowSpan</a> classes. <a href="#a8ebd411a505f41da49085559bdc9685e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2769e7f4b078110dae0ca454481d5e41">unescapeCRef</a> (QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a> (const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f244300da7fd232ca1e4a858c12df3">setParent</a> (DocNodeVariant *n, DocNodeVariant *newParent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a> (DocNodeVariant *root, DocNodeList &amp;children)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a9f35c62c2ef88e116f4edea12c038">findAttribute</a> (const HtmlAttribList &amp;tagHtmlAttribs, const char *attrName, QCString *result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a> (DocParser *parser, const DocNodeVariant *n)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f93ac679cfacdfe2439e33520d54a4">g_sectionLevelToName</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3728393a128acabd46175c3dc101a784">g_plantumlEngine</a> = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e94735e6ecdae48725e0c4254a2689">INTERNAL_ASSERT</a>(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
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

## Typedefs

### RowSpanList {#a8ebd411a505f41da49085559bdc9685e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;ActiveRowSpan&gt; RowSpanList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

List of <a href="/web-doxygen/docs/api/structs/activerowspan">ActiveRowSpan</a> classes.

Definition at line 2283 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ebd411a505f41da49085559bdc9685e">2283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> std::vector&lt;ActiveRowSpan&gt; <a href="#a8ebd411a505f41da49085559bdc9685e">RowSpanList</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### checkIfHtmlEndTagEndsAutoList() {#adbe932c521ee8cde5ccc5cdca438fa5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkIfHtmlEndTagEndsAutoList (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n)</td>
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



Definition at line 5598 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbe932c521ee8cde5ccc5cdca438fa5f">5598</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5599</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// expected hierarchy:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// 1    DocAutoListItem &lt;- n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// 2  DocAutoList       &lt;- parent(n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5603</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// 3 DocPara            &lt;- parent(parent(n))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5604</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5605</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// step 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5606</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!std::get_if&lt;DocAutoListItem&gt;(n)) </span><span class="doxyHighlightComment">// not inside a auto list item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5607</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5609</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5610</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5611</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// step 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5612</span><span class="doxyLineContent"><span class="doxyHighlight">  n = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5614</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> docAutoList = std::get_if&lt;DocAutoList&gt;(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5615</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (docAutoList) </span><span class="doxyHighlightComment">// capture indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5616</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5617</span><span class="doxyLineContent"><span class="doxyHighlight">    indent = docAutoList-&gt;indent();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5618</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5620</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5622</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5623</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// step 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5625</span><span class="doxyLineContent"><span class="doxyHighlight">  n = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5626</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> docPara = std::get_if&lt;DocPara&gt;(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5627</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (docPara)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5628</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5629</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagNameLower = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a>).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5630</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> topStyleChange = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a> &amp;stack) -&gt; </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5631</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5632</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::get&lt;DocStyleChange&gt;(*stack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5633</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5634</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.empty() ||                                                     </span><span class="doxyHighlightComment">// no style change</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5636</span><span class="doxyLineContent"><span class="doxyHighlight">        (topStyleChange(parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>).tagName()==tagNameLower &amp;&amp;                    </span><span class="doxyHighlightComment">// correct style change</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5637</span><span class="doxyLineContent"><span class="doxyHighlight">         topStyleChange(parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>).position()!=parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.size()) </span><span class="doxyHighlightComment">// wrong position, so normal close</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5638</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5639</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5640</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// insert an artificial 'end of autolist' marker and parse again</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5641</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> indentStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5642</span><span class="doxyLineContent"><span class="doxyHighlight">      indentStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5643</span><span class="doxyLineContent"><span class="doxyHighlight">      parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#ab8df06c9b8d04453c03cd380baa8e0b8">unputString</a>(</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">+indentStr+</span><span class="doxyHighlightStringLiteral">".\\ilinebr"</span><span class="doxyHighlight">+indentStr+</span><span class="doxyHighlightStringLiteral">"&lt;/"</span><span class="doxyHighlight">+parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a>+</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5644</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5645</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5646</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5647</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">5648</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">TokenInfo::name</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">DocParserContext::nodeStack</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">DocParserContext::styleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a> and <a href="/web-doxygen/docs/api/classes/doctokenizer/#ab8df06c9b8d04453c03cd380baa8e0b8">DocTokenizer::unputString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>.
</div>
</div>

### findAttribute() {#a89a9f35c62c2ef88e116f4edea12c038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findAttribute (const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; tagHtmlAttribs, const char * attrName, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * result)</td>
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



Definition at line 4888 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89a9f35c62c2ef88e116f4edea12c038">4888</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a89a9f35c62c2ef88e116f4edea12c038">findAttribute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;tagHtmlAttribs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4889</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *attrName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4890</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4891</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4892</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4893</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : tagHtmlAttribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4894</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4895</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==attrName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4896</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4897</span><span class="doxyLineContent"><span class="doxyHighlight">      *result = opt.value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4898</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4899</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4900</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4902</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.
</div>
</div>

### flattenParagraphs() {#a71dd66dcbef8ad6aa74feb1e87e2a06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void flattenParagraphs (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * root, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
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



Definition at line 825 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71dd66dcbef8ad6aa74feb1e87e2a06b">825</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *root,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> newChildren;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dn : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *para = std::get_if&lt;DocPara&gt;(&amp;dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (para)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlightComment">      //// move the children of the paragraph to the end of the newChildren list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">      newChildren.<a href="/web-doxygen/docs/api/structs/docnodelist/#a6bb13c84c8ad84d77584f6a3ec24a2a9">move_append</a>(para-&gt;<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// replace the children list by the newChildren list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/classes/growvector/#a198715b8f95bc34cb020ae11170470f7">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a6bb13c84c8ad84d77584f6a3ec24a2a9">move_append</a>(newChildren);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// reparent the children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a91f244300da7fd232ca1e4a858c12df3">setParent</a>(&amp;cn,root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// we also need to set the parent for each child of cn, as cn's address may have changed.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt_children = <a href="/web-doxygen/docs/api/files/src/docnode-h/#a757dcb2ad9a839e761e6808f8cb51a04">call_method_children</a>(&amp;cn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt_children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ccn : *opt_children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a91f244300da7fd232ca1e4a858c12df3">setParent</a>(&amp;ccn,&amp;cn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-h/#a757dcb2ad9a839e761e6808f8cb51a04">call\_method\_children</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a198715b8f95bc34cb020ae11170470f7">GrowVector&lt; T &gt;::clear</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#a6bb13c84c8ad84d77584f6a3ec24a2a9">DocNodeList::move\_append</a> and <a href="#a91f244300da7fd232ca1e4a858c12df3">setParent</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a> and <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>.
</div>
</div>

### setParent() {#a91f244300da7fd232ca1e4a858c12df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setParent (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * newParent)</td>
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



Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91f244300da7fd232ca1e4a858c12df3">118</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91f244300da7fd232ca1e4a858c12df3">setParent</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *newParent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  std::visit([&amp;](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;&amp;x)-&gt;</span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> x.setParent(newParent); }, *n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>.
</div>
</div>

### stripKnownExtensions() {#a232984936769698de5f6d1ffaabf12a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString stripKnownExtensions (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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




Strips known html and tex extensions from <em>text</em>.

Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a232984936769698de5f6d1ffaabf12a6">103</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a232984936769698de5f6d1ffaabf12a6">stripKnownExtensions</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".tex"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>.length())==</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/doclink/#ac29d67178173446fbc14dd28378daec3">DocLink::DocLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a> and <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>.
</div>
</div>

### unescapeCRef() {#a2769e7f4b078110dae0ca454481d5e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void unescapeCRef (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2769e7f4b078110dae0ca454481d5e41">81</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2769e7f4b078110dae0ca454481d5e41">unescapeCRef</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">) c=</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">) c=</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  result=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  result=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  s = result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_plantumlEngine {#a3728393a128acabd46175c3dc101a784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringUnorderedSet g_plantumlEngine</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  "uml", "bpm", "wire", "dot", "ditaa",
  "salt", "math", "latex", "gantt", "mindmap",
  "wbs", "yaml", "creole", "json", "flow",
  "board", "git", "hcl", "regex", "ebnf",
  "files", "chen", "chronology"
}
</div>
</dd>
</dl>

Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3728393a128acabd46175c3dc101a784">69</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> <a href="#a3728393a128acabd46175c3dc101a784">g_plantumlEngine</a> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"uml"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"bpm"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"wire"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"ditaa"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"salt"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"math"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"latex"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"gantt"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"mindmap"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"wbs"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"yaml"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"creole"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"json"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"flow"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"board"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"git"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"hcl"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"regex"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"ebnf"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"files"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"chen"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"chronology"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.
</div>
</div>

### g\_sectionLevelToName {#a06f93ac679cfacdfe2439e33520d54a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_sectionLevelToName[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
{
  "page",
  "section",
  "subsection",
  "subsubsection",
  "paragraph",
  "subparagraph"
}
</div>
</dd>
</dl>

Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06f93ac679cfacdfe2439e33520d54a4">56</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a06f93ac679cfacdfe2439e33520d54a4">g_sectionLevelToName</a>[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"page"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"section"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"subsection"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"subsubsection"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"paragraph"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"subparagraph"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AUTO\_TRACE {#a210042a14f3a393be09c743c219126ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a210042a14f3a393be09c743c219126ae">46</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE(...)      (void)0</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac8b137671c00e2c3c383420e4b04ba1a">MemberDefImpl::\_computeLinkableInProject</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41e981742ff67fe146064ae772af3f72">SymbolResolver::Private::accessibleViaUsingDefinition</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a48485218477ceb4bff6608fb8c7d1d45">ModuleDefImpl::addClassToModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3bed85d27e567e04fe01b0192a58db97">ModuleDefImpl::addConceptToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">ModuleDefImpl::addExportedModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#afbaf12976ba6620dccd9067b26244e51">ModuleDefImpl::addHeader</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a5c564c642161994958220628ac58aef8">ModuleManager::addHeader</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#acabf04c9722d33c1b5240a56ad93d572">ModuleDefImpl::addImport</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5c29617e942b0f91f94f5b362cb2fa67">addLocalObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a97d3881f19cc6d4afb3d7a7376ec222b">ClassDefImpl::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a0b89a353206730e5f1ce65366c49f92f">ClassDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acb9600203ce6656264dca810825c7cb1">buildClassDocList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad716b06348a4b4d2f0909ed729c8db38">buildClassList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af211d864d0f6ed4ab22c3b133d9f9d7f">buildConceptDocList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a30d9c2cd03c7c474fb65f46878d0ae1a">buildConceptList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac808ed1ddf94dd08b95d1ee433e96359">buildDictionaryList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb157ec5dd9aa56ca80abcf1fd5099f7">buildInterfaceAndServiceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6c44f1592724165dbf7e5a36be496b5d">buildSequenceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a685b08b025bb0139299eb40a0704df31">buildVarList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abd67a3f8ef0181d7a4179931452449df">ModuleManager::collectExportedSymbols</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a56ebe7e944c71ea43b47da0b331789ab">ModuleManager::collectExportedSymbolsRecursively</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae736b4f85b5f2d2b1cf3bfd22aa2b1cb">DirDefImpl::computeDependencies</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#abf61ee43dee8d980a631843cd26b71cb">computeDirDependencies</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4130a395a6948c0202fc85ac018a6236">computeMemberReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a803ce79833ba42275ae6a45c695fe24c">ClassDefImpl::containsOverload</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a7e2356fcdbce7babc9b65ba24be66fc9">ModuleManager::createModuleDef</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a08a51ed53b0b61d7839aa40d04080f9d">DirDefImpl::createNewDir</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4867a5cabf355b71e9540e4316ba17dd">distributeConceptGroups</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8d91af0a6807cf2a6b66896bfdef6732">encodeDirName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae13abaf328534f92b57bb6af8208f31d">findBaseClassesForClass</a>, <a href="/web-doxygen/docs/api/structs/codefragmentmanager/private/fragmentinfo/#aa83070e84b415c54820d479386998ea2">CodeFragmentManager::Private::FragmentInfo::findBlockMarkers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e693bc88f52ca1575ff19ce054824c6">findFunctionPtr</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a000332499c2ed82b4b4e2f0318bc98fa">findInheritedTemplateInstances</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5aa9158e081cf448e0822afbb0ac760c">findMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab9145bae1ceb13c316c9ced4b3bbf1d9">findModuleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a52d28be272ce56e336d53cec31a62c18">findObjCMethodDefinitions</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad9ce767127c1fe73995ebae8badaab75">findUsedTemplateInstances</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#aeb63b0db3ac92afc6ef8fd7a34129001">generateDirDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0cb7d6c9c783e1376142dbe33d01f821">generateDocsForClassList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1cdf977b93a419aaef78c31944c7dd00">generateXRefPages</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa691b51bc5cab49b921809b293c2fa61">ClassDefImpl::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a6ed55f11d0d0cb39761ce7dd7dd51655">DirDefImpl::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docparser/#adf24a6cf025048b8a3235ca2c897dc06">DocParser::handleAnchor</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ac2433e9fbc80306d6ae28ff94a019068">DocPara::handleHtmlHeader</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8cdd911ef9ea557d2fd2a0f034efcaa4">DocPara::handleILine</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a334b7286f0a4445d85743cce35a3c090">DocParser::handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab8ac10aa71d5d6c021a6e2f08df318f8">DocParser::handlePrefix</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docparser/#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>, <a href="/web-doxygen/docs/api/classes/docparser/#af097a0f67abbe29e09a9956e88eb7642">DocParser::handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ab5639797f3123c08c83f16819f7a74d7">DocPara::handleVhdlFlow</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">DocPara::injectToken</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a43912d740c8be598e342b29e8eee5b26">ClassDefImpl::insertExplicitTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af3eab25ba334db0ed299983b354a89cb">ClassDefImpl::insertTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">SymbolResolver::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5628c6052a120856d53921f8746d0251">Markdown::Private::isHeaderline</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a52cc252e59332d38e224e11bd019f632">matchCanonicalTypes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a294b2f8587b6f511bac156c5e945ff34">matchTemplateArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad091d341c14ea4fbd41ca45921d5b75f">mergeCategories</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#abc751e8cc79b9f7cc8040ba7ecce6e1f">DirDefImpl::mergeDirectoryInTree</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a74e7d2dfc4dd50bd19a070adcdd48b71">ModuleDefImpl::mergeSymbolsFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2907cfb329df93257c355ceaa29993d7">organizeSubGroupsFiltered</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#ab9cc38fde444889a618974f396bf36ed">DocInternalRef::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae28f1a48382c964843997257b8d171f9">parseFilesSingleThreading</a>, <a href="/web-doxygen/docs/api/classes/coutlineparser/#a5bf5190ffb4fc52b45fc6b22895a6fbf">COutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a7f705aecadc99bf342402a00f7c7fc38">DocHtmlDetails::parseSummary</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0bb20b07bce14eca215477b9ec05adbd">Markdown::Private::processEmphasis1</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#abbb763f2449b932ef3468560e30a0478">Markdown::Private::processEmphasis2</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a4041a1e946c4402894bfff49b611e63b">Markdown::Private::processEmphasis3</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a7ef2d648f867a25fac44f095b89630c6">Markdown::Private::processHtmlTag</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#ac0a9e3273eb76713a9e197d5be61e11a">Markdown::Private::processInline</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#adafbef72995b1327272b82a2b2075480">Markdown::Private::processNmdash</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0f211ac431de2f23ca4874c125ab1551">Markdown::Private::processQuoted</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">DocParser::readTextFileByName</a>, <a href="/web-doxygen/docs/api/files/src/codefragment-cpp/#a8c33a344ab42361aefb90541f2be4e6e">readTextFileByName</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4ec82e2c6d7aac89ee42416993ce59da">ModuleManager::resolveImports</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a9a5ccba7154d90c27699bad5517f8b18">ModuleManager::resolvePartitions</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a739c707d2150c5b2115fa731694eaeec">SymbolResolver::resolveSymbol</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2d8e8d7d9dffa9a72e2ea7e9c13785d4">warnUndocumentedNamespaces</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a783230ed87aae779b1e405abfe5b9954">ClassDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a494fc3fc6c848a37caa06e5d85854ffe">Markdown::Private::writeFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.
</div>
</div>

### AUTO\_TRACE\_ADD {#a05be586784f268b947ad777aa316c4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE_ADD(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05be586784f268b947ad777aa316c4e6">47</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE_ADD(...)  (void)0</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac8b137671c00e2c3c383420e4b04ba1a">MemberDefImpl::\_computeLinkableInProject</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41e981742ff67fe146064ae772af3f72">SymbolResolver::Private::accessibleViaUsingDefinition</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a5c564c642161994958220628ac58aef8">ModuleManager::addHeader</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5c29617e942b0f91f94f5b362cb2fa67">addLocalObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abd67a3f8ef0181d7a4179931452449df">ModuleManager::collectExportedSymbols</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae736b4f85b5f2d2b1cf3bfd22aa2b1cb">DirDefImpl::computeDependencies</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#abf61ee43dee8d980a631843cd26b71cb">computeDirDependencies</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a08a51ed53b0b61d7839aa40d04080f9d">DirDefImpl::createNewDir</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4867a5cabf355b71e9540e4316ba17dd">distributeConceptGroups</a>, <a href="/web-doxygen/docs/api/structs/codefragmentmanager/private/fragmentinfo/#aa83070e84b415c54820d479386998ea2">CodeFragmentManager::Private::FragmentInfo::findBlockMarkers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad091d341c14ea4fbd41ca45921d5b75f">mergeCategories</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2907cfb329df93257c355ceaa29993d7">organizeSubGroupsFiltered</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4ec82e2c6d7aac89ee42416993ce59da">ModuleManager::resolveImports</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### AUTO\_TRACE\_EXIT {#a81912d2a3d12aab7a9e546e5299e2e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE_EXIT(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81912d2a3d12aab7a9e546e5299e2e09">48</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE_EXIT(...) (void)0</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41e981742ff67fe146064ae772af3f72">SymbolResolver::Private::accessibleViaUsingDefinition</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a803ce79833ba42275ae6a45c695fe24c">ClassDefImpl::containsOverload</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8d91af0a6807cf2a6b66896bfdef6732">encodeDirName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6731b64072d6a924bed7534d9a6c041b">extractCanonicalType</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e693bc88f52ca1575ff19ce054824c6">findFunctionPtr</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docparser/#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">SymbolResolver::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5628c6052a120856d53921f8746d0251">Markdown::Private::isHeaderline</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a294b2f8587b6f511bac156c5e945ff34">matchTemplateArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0bb20b07bce14eca215477b9ec05adbd">Markdown::Private::processEmphasis1</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#abbb763f2449b932ef3468560e30a0478">Markdown::Private::processEmphasis2</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a4041a1e946c4402894bfff49b611e63b">Markdown::Private::processEmphasis3</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#adafbef72995b1327272b82a2b2075480">Markdown::Private::processNmdash</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0f211ac431de2f23ca4874c125ab1551">Markdown::Private::processQuoted</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a739c707d2150c5b2115fa731694eaeec">SymbolResolver::resolveSymbol</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.
</div>
</div>

### INTERNAL\_ASSERT {#a70e94735e6ecdae48725e0c4254a2689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INTERNAL_ASSERT(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70e94735e6ecdae48725e0c4254a2689">51</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define INTERNAL_ASSERT(x) do {} while(0)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a> and <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
