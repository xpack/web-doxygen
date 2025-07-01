---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotnode
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotNode` Class Reference

A node in a dot graph. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DotNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotnode-h">src/dotnode.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LabelStyle { <a href="#acd975dffca58fc0d6bbcae4b37e280ed">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TruncState { <a href="#ac40de94762a7659599b2056942373102">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> (DotGraph *graph, const QCString &amp;lab, const QCString &amp;tip, const QCString &amp;url, bool rootNode=FALSE, const ClassDef *cd=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54555a412724c31181a40a50213e38e">addChild</a> (DotNode *n, EdgeInfo::Colors edgeColor=EdgeInfo::Purple, EdgeInfo::Styles edgeStyle=EdgeInfo::Solid, const QCString &amp;edgeLab=QCString(), const QCString &amp;edgeURL=QCString(), int edgeLabCol=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f7fc0d1caa3e53622039e86903b04e">addParent</a> (DotNode *n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a> (DotNodeRefVector &amp;deletedList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62686e145c94129d85409214fb3e0571">removeChild</a> (DotNode *n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a36f34067293e7428ae7ea527678fee">removeParent</a> (DotNode *n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f42851921caf9442ed2c4e4468b695">findParent</a> (DotNode *n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a> (TextStream &amp;t, GraphType gt, GraphOutputFormat f, bool topDown, bool toChildren, bool backArrows)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a> (TextStream &amp;t, bool isClassGraph) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a> (TextStream &amp;t, bool isClassGraph) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a> (TextStream &amp;t) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a> (TextStream &amp;t, GraphType gt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb314bd0d605efa7019319e3da26870">writeUrl</a> (TextStream &amp;t) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a> (TextStream &amp;t, GraphType gt, GraphOutputFormat f, bool hasNonReachableChildren) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a> (TextStream &amp;t, GraphType gt, GraphOutputFormat f, const DotNode *cn, const EdgeInfo *ei, bool topDown, bool pointBack=TRUE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead1705f4e6586bd7ba613fdda2e7241">label</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac40de94762a7659599b2056942373102">TruncState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcfb83215c88dcdd5c39391547e3882b">isTruncated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778848585e3ab3d63610f568c7299511">isRenumbered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac192b74541fe778106f8c17e970dc489">hasDocumentation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09c516ca773d02f6af1536df5d47498">isWritten</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27692f33c86a577ad85ab7176539d4de">clearWriteFlag</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a> (int &amp;number)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d245f9612e50c197d2df5392bfae2bb">markRenumbered</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bc5bd51995cf7afba4f94f895e0ce7">markHasDocumentation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54523891e16f0ad2c98f745983f0ed1c">setSubgraphId</a> (int id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8eb3aaf830fe2685ebc36bf783857a">colorConnectedNodes</a> (int curColor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a> (int distance)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a> (bool b=TRUE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a> (bool b=TRUE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9b5bf9d87bd3f71d4e7d1e6f8c6239">parents</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a27cb2e97ee7dd89763d1e5ee7f936324">EdgeInfoVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">setNodeId</a> (int number)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb54967e727ba0255965c24265cfb376">m_graph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
label text <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd471e954ba6e4bdd9060787da53286">m_tooltip</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
node's tooltip <a href="#a1cd471e954ba6e4bdd9060787da53286">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
url of the node (format: remote$local) <a href="#afeafe76686b1e932aacbd7e9e854ff26">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
list of parent nodes (incoming arrows) <a href="#aa397d81f5f600725c2a98d77e3f27908">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1234b87999769323c75747182e7b9d1">m_children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
list of child nodes (outgoing arrows) <a href="#ac1234b87999769323c75747182e7b9d1">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/dotnode-h/#a27cb2e97ee7dd89763d1e5ee7f936324">EdgeInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
edge info for each child <a href="#a761040a5361299f900b49c35c2462382">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08bcf1483374985a785829e702b4f0d">m_deleted</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
used to mark a node as deleted <a href="#ae08bcf1483374985a785829e702b4f0d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
used to mark a node as written <a href="#a53c2882a93930d9fc813d4e6152aa475">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3911b863e988573b48bd22cb81c49829">m_hasDoc</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
used to mark a node as documented <a href="#a3911b863e988573b48bd22cb81c49829">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m_isRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
indicates if this is a root node <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
class representing this node (can be 0) <a href="#acad63761d0fcce398f2d8a663fd1cfa8">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab092b4fec02c4420c518ad325cc4b175">m_visible</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
is the node visible in the output <a href="#ab092b4fec02c4420c518ad325cc4b175">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac40de94762a7659599b2056942373102">TruncState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408a1095014b55475e7138d861597b69">m_truncated</a> = <a href="#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
does the node have non-visible children/parents <a href="#a408a1095014b55475e7138d861597b69">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7792be9d15ff8fc45863bce185e3e328">m_distance</a> = 1000</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
shortest path to the root node <a href="#a7792be9d15ff8fc45863bce185e3e328">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m_renumbered</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
indicates if the node has been renumbered (to prevent endless loops) <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa257c0a638d14c60ba4714df5a9845b">m_subgraphId</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748649462fd72baa804eccd77fcfa612">deleteNodes</a> (DotNode *node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a> (const QCString &amp;, LabelStyle=LabelStyle::Plain)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c9b1e1192faac2bf956a6a3043be0c">placeholderUrl</a> = "-"</td>
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

A node in a dot graph.

Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxySectionDef">

## Enumerations

### LabelStyle {#acd975dffca58fc0d6bbcae4b37e280ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class DotNode::LabelStyle </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Plain<a id="acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">List<a id="acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Table<a id="acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd975dffca58fc0d6bbcae4b37e280ed">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#acd975dffca58fc0d6bbcae4b37e280ed">LabelStyle</a> { <a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">Plain</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">List</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">Table</a> };</span></span></div>

</div>

</div>
</div>

### TruncState {#ac40de94762a7659599b2056942373102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DotNode::TruncState </td>
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
<td class="doxyEnumItemName">Unknown<a id="ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Truncated<a id="ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Untruncated<a id="ac40de94762a7659599b2056942373102aa2b953f9ab3592ebf7903ff35643eb60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#ac40de94762a7659599b2056942373102">TruncState</a> { <a href="#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">Unknown</a>, <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a>, <a href="#ac40de94762a7659599b2056942373102aa2b953f9ab3592ebf7903ff35643eb60">Untruncated</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DotNode() {#a48f504e2687c7ccf1f010ab9a1aeebf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode::DotNode (<a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a> * graph, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tip, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; url, bool rootNode=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 327 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">327</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode::DotNode</a>(<a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a> *graph,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tip, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;url,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isRoot,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#aeb54967e727ba0255965c24265cfb376">m_graph</a>(graph)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>(graph-&gt;getNextNodeNumber())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>(lab)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#a1cd471e954ba6e4bdd9060787da53286">m_tooltip</a>(tip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>(url)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m_isRoot</a>(isRoot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>(cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m\_classDef</a>, <a href="#aeb54967e727ba0255965c24265cfb376">m\_graph</a>, <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m\_isRoot</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#a1cd471e954ba6e4bdd9060787da53286">m\_tooltip</a> and <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>.

Referenced by <a href="#ac54555a412724c31181a40a50213e38e">addChild</a>, <a href="#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>, <a href="#a748649462fd72baa804eccd77fcfa612">deleteNodes</a>, <a href="#a05f42851921caf9442ed2c4e4468b695">findParent</a>, <a href="#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a>, <a href="#a92bc5bd51995cf7afba4f94f895e0ce7">markHasDocumentation</a>, <a href="#a62686e145c94129d85409214fb3e0571">removeChild</a>, <a href="#a2a36f34067293e7428ae7ea527678fee">removeParent</a>, <a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">setNodeId</a> and <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addChild() {#ac54555a412724c31181a40a50213e38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::addChild (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228">EdgeInfo::Colors</a> edgeColor=<a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5">EdgeInfo::Styles</a> edgeStyle=<a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; edgeLab=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; edgeURL=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), int edgeLabCol=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 339 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac54555a412724c31181a40a50213e38e">339</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac54555a412724c31181a40a50213e38e">DotNode::addChild</a>(<a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *n,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228">EdgeInfo::Colors</a> edgeColor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5">EdgeInfo::Styles</a> edgeStyle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;edgeLab,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;edgeURL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> edgeLabCol</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>.push_back(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>.emplace_back(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">      edgeColor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      edgeStyle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">      edgeLab,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      edgeURL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      edgeLabCol==-1 ? edgeColor : edgeLabCol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a> and <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>.
</div>
</div>

### addParent() {#a98f7fc0d1caa3e53622039e86903b04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::addParent (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 356 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98f7fc0d1caa3e53622039e86903b04e">356</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98f7fc0d1caa3e53622039e86903b04e">DotNode::addParent</a>(<a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.push_back(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>.
</div>
</div>

### children() {#ad8b1f38e1403f73fc4f8745b5fbe00c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DotNodeRefVector &amp; DotNode::children ()</td>
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



Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp;<a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>; }</span></span></div>

</div>


Reference <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#af3afda59cf627bb7ebb4771ad47fcfbc">DotCallGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a1a4d42a2191cbdac155f1f9b67c4bfb5">DotInclDepGraph::determineVisibleNodes</a> and <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

### clearWriteFlag() {#a27692f33c86a577ad85ab7176539d4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::clearWriteFlag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 888 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27692f33c86a577ad85ab7176539d4de">888</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27692f33c86a577ad85ab7176539d4de">DotNode::clearWriteFlag</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pn : <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>)  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pn-&gt;isWritten()) pn-&gt;clearWriteFlag();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>) </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cn-&gt;isWritten()) cn-&gt;clearWriteFlag();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a> and <a href="#a53c2882a93930d9fc813d4e6152aa475">m\_written</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>.
</div>
</div>

### colorConnectedNodes() {#abb8eb3aaf830fe2685ebc36bf783857a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::colorConnectedNodes (int curColor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 119 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 895 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb8eb3aaf830fe2685ebc36bf783857a">895</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb8eb3aaf830fe2685ebc36bf783857a">DotNode::colorConnectedNodes</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> curColor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cn-&gt;subgraphId()==-1) </span><span class="doxyHighlightComment">// uncolored child node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">      cn-&gt;setSubgraphId(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">      cn-&gt;markAsVisible();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">      cn-&gt;colorConnectedNodes(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("coloring node %s (%p): %d\n",qPrint(cn-&gt;label()),cn,cn-&gt;subgraphId());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pn : <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pn-&gt;subgraphId()==-1) </span><span class="doxyHighlightComment">// uncolored parent node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">      pn-&gt;setSubgraphId(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">      pn-&gt;markAsVisible();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">      pn-&gt;colorConnectedNodes(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("coloring node %s (%p): %d\n",qPrint(pn-&gt;label()),pn,pn-&gt;subgraphId());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a> and <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>.
</div>
</div>

### deleteNode() {#ae2c044edad92d6008b036ae6c1f97551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::deleteNode (<a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp; deletedList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 373 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2c044edad92d6008b036ae6c1f97551">373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae2c044edad92d6008b036ae6c1f97551">DotNode::deleteNode</a>(<a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp;deletedList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae08bcf1483374985a785829e702b4f0d">m_deleted</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// avoid recursive loops in case the graph has cycles</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae08bcf1483374985a785829e702b4f0d">m_deleted</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// delete all parent nodes of this node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pn : <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    pn-&gt;deleteNode(deletedList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// delete all child nodes of this node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">    cn-&gt;deleteNode(deletedList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add this node to the list of deleted nodes.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  deletedList.push_back(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#ae08bcf1483374985a785829e702b4f0d">m\_deleted</a>, <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a748649462fd72baa804eccd77fcfa612">deleteNodes</a>.
</div>
</div>

### distance() {#a196e6efc147272506e3e0564dfe47bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::distance ()</td>
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



Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a196e6efc147272506e3e0564dfe47bfe">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7792be9d15ff8fc45863bce185e3e328">m_distance</a>; }</span></span></div>

</div>


Reference <a href="#a7792be9d15ff8fc45863bce185e3e328">m\_distance</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotcallgraph/#af3afda59cf627bb7ebb4771ad47fcfbc">DotCallGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a1a4d42a2191cbdac155f1f9b67c4bfb5">DotInclDepGraph::determineVisibleNodes</a> and <a href="#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>.
</div>
</div>

### edgeInfo() {#a323a0f1b9913242153ef1f84abb05a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EdgeInfoVector &amp; DotNode::edgeInfo ()</td>
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



Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a323a0f1b9913242153ef1f84abb05a60">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a27cb2e97ee7dd89763d1e5ee7f936324">EdgeInfoVector</a> &amp;<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>; }</span></span></div>

</div>


Reference <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>.

Referenced by <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### findParent() {#a05f42851921caf9442ed2c4e4468b695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::findParent (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n)</td>
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



Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 396 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05f42851921caf9442ed2c4e4468b695">396</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a05f42851921caf9442ed2c4e4468b695">DotNode::findParent</a>( <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *n )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find(<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.begin(),<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.end(),n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.end() ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.begin()) : -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>.
</div>
</div>

### hasDocumentation() {#ac192b74541fe778106f8c17e970dc489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::hasDocumentation ()</td>
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



Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac192b74541fe778106f8c17e970dc489">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac192b74541fe778106f8c17e970dc489">hasDocumentation</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3911b863e988573b48bd22cb81c49829">m_hasDoc</a>; }</span></span></div>

</div>


Reference <a href="#a3911b863e988573b48bd22cb81c49829">m\_hasDoc</a>.
</div>
</div>

### isRenumbered() {#a778848585e3ab3d63610f568c7299511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::isRenumbered ()</td>
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



Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a778848585e3ab3d63610f568c7299511">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a778848585e3ab3d63610f568c7299511">isRenumbered</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m_renumbered</a>; }</span></span></div>

</div>


Reference <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m\_renumbered</a>.

Referenced by <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>.
</div>
</div>

### isTruncated() {#adcfb83215c88dcdd5c39391547e3882b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TruncState DotNode::isTruncated ()</td>
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



Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcfb83215c88dcdd5c39391547e3882b">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac40de94762a7659599b2056942373102">TruncState</a> <a href="#adcfb83215c88dcdd5c39391547e3882b">isTruncated</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a408a1095014b55475e7138d861597b69">m_truncated</a>; }</span></span></div>

</div>


Reference <a href="#a408a1095014b55475e7138d861597b69">m\_truncated</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>.
</div>
</div>

### isVisible() {#a9e97a698e9e6460cd7fac782e38f0ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::isVisible ()</td>
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



Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e97a698e9e6460cd7fac782e38f0ce7">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab092b4fec02c4420c518ad325cc4b175">m_visible</a>; }</span></span></div>

</div>


Reference <a href="#ab092b4fec02c4420c518ad325cc4b175">m\_visible</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#af3afda59cf627bb7ebb4771ad47fcfbc">DotCallGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a1a4d42a2191cbdac155f1f9b67c4bfb5">DotInclDepGraph::determineVisibleNodes</a>.
</div>
</div>

### isWritten() {#aa09c516ca773d02f6af1536df5d47498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::isWritten ()</td>
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



Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa09c516ca773d02f6af1536df5d47498">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa09c516ca773d02f6af1536df5d47498">isWritten</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a>; }</span></span></div>

</div>


Reference <a href="#a53c2882a93930d9fc813d4e6152aa475">m\_written</a>.
</div>
</div>

### label() {#aead1705f4e6586bd7ba613fdda2e7241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotNode::label ()</td>
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



Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aead1705f4e6586bd7ba613fdda2e7241">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aead1705f4e6586bd7ba613fdda2e7241">label</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>; }</span></span></div>

</div>


Reference <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>.
</div>
</div>

### markAsTruncated() {#a543c8aa7d944877ff050dbdb9bbfd7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode &amp; DotNode::markAsTruncated (bool b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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



Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a543c8aa7d944877ff050dbdb9bbfd7db">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>&amp; <a href="#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) { <a href="#a408a1095014b55475e7138d861597b69">m_truncated</a>=b ? <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a> : <a href="#ac40de94762a7659599b2056942373102aa2b953f9ab3592ebf7903ff35643eb60">Untruncated</a>; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a408a1095014b55475e7138d861597b69">m\_truncated</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a> and <a href="#ac40de94762a7659599b2056942373102aa2b953f9ab3592ebf7903ff35643eb60">Untruncated</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>.
</div>
</div>

### markAsVisible() {#a2592b8669b2aba1c2f0476e1011d48cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::markAsVisible (bool b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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



Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2592b8669b2aba1c2f0476e1011d48cd">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) { <a href="#ab092b4fec02c4420c518ad325cc4b175">m_visible</a>=b; }</span></span></div>

</div>


References <a href="#ab092b4fec02c4420c518ad325cc4b175">m\_visible</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#ab6cc9aafe7eb910bca59ef9cea2dff14">DotGroupCollaboration::addCollaborationMember</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#af3afda59cf627bb7ebb4771ad47fcfbc">DotCallGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a1a4d42a2191cbdac155f1f9b67c4bfb5">DotInclDepGraph::determineVisibleNodes</a>.
</div>
</div>

### markHasDocumentation() {#a92bc5bd51995cf7afba4f94f895e0ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode &amp; DotNode::markHasDocumentation ()</td>
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



Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92bc5bd51995cf7afba4f94f895e0ce7">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>&amp; <a href="#a92bc5bd51995cf7afba4f94f895e0ce7">markHasDocumentation</a>() { <a href="#a3911b863e988573b48bd22cb81c49829">m_hasDoc</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#a3911b863e988573b48bd22cb81c49829">m\_hasDoc</a>.
</div>
</div>

### markRenumbered() {#a1d245f9612e50c197d2df5392bfae2bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::markRenumbered ()</td>
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



Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d245f9612e50c197d2df5392bfae2bb">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d245f9612e50c197d2df5392bfae2bb">markRenumbered</a>()          { <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m_renumbered</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m\_renumbered</a>.

Referenced by <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>.
</div>
</div>

### number() {#a3c08a5ee367bbf4c58c719ff7f8e0fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::number ()</td>
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



Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">  <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>; }</span></span></div>

</div>


Reference <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>.

Referenced by <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>, <a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">setNodeId</a> and <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>.
</div>
</div>

### parents() {#aca9b5bf9d87bd3f71d4e7d1e6f8c6239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DotNodeRefVector &amp; DotNode::parents ()</td>
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



Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca9b5bf9d87bd3f71d4e7d1e6f8c6239">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> &amp;<a href="#aca9b5bf9d87bd3f71d4e7d1e6f8c6239">parents</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>; }</span></span></div>

</div>


Reference <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a> and <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>.
</div>
</div>

### removeChild() {#a62686e145c94129d85409214fb3e0571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::removeChild (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 361 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62686e145c94129d85409214fb3e0571">361</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a62686e145c94129d85409214fb3e0571">DotNode::removeChild</a>(<a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find(<a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>.begin(),<a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>.end(),n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>.end()) <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>.
</div>
</div>

### removeParent() {#a2a36f34067293e7428ae7ea527678fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::removeParent (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 367 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a36f34067293e7428ae7ea527678fee">367</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a36f34067293e7428ae7ea527678fee">DotNode::removeParent</a>(<a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find(<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.begin(),<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.end(),n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.end()) <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>.
</div>
</div>

### renumberNodes() {#a4e9da1f53e500d73aa8997ead79093fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::renumberNodes (int &amp; number)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 922 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e9da1f53e500d73aa8997ead79093fb">922</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4e9da1f53e500d73aa8997ead79093fb">DotNode::renumberNodes</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a778848585e3ab3d63610f568c7299511">isRenumbered</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if DEBUG_RENUMBERING</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"%3d: "</span><span class="doxyHighlight">,<a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; level; i++) printf(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"&gt; %s old = %d new = %d\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>),<a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>,<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    level++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a> = <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1d245f9612e50c197d2df5392bfae2bb">markRenumbered</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">      cn-&gt;renumberNodes(<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pn : <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">      pn-&gt;renumberNodes(<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if DEBUG_RENUMBERING</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">    level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"%3d: "</span><span class="doxyHighlight">,<a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; level; i++) printf(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"&lt; %s assigned = %d\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>),<a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a778848585e3ab3d63610f568c7299511">isRenumbered</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>, <a href="#a1d245f9612e50c197d2df5392bfae2bb">markRenumbered</a>, <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a>.
</div>
</div>

### setDistance() {#a21956cf8ee9e3f8b750c221f6d00ee84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::setDistance (int distance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 391 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21956cf8ee9e3f8b750c221f6d00ee84">391</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a21956cf8ee9e3f8b750c221f6d00ee84">DotNode::setDistance</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a>&lt;<a href="#a7792be9d15ff8fc45863bce185e3e328">m_distance</a>) <a href="#a7792be9d15ff8fc45863bce185e3e328">m_distance</a> = <a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a> and <a href="#a7792be9d15ff8fc45863bce185e3e328">m\_distance</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>.
</div>
</div>

### setNodeId() {#ae1dc99d158ddb9a5ce63dda67ea843f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode &amp; DotNode::setNodeId (int number)</td>
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



Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> &amp;<a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">setNodeId</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>) { <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>=<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>


References <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a> and <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>.
</div>
</div>

### setSubgraphId() {#a54523891e16f0ad2c98f745983f0ed1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::setSubgraphId (int id)</td>
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



Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54523891e16f0ad2c98f745983f0ed1c">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a54523891e16f0ad2c98f745983f0ed1c">setSubgraphId</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)     { <a href="#afa257c0a638d14c60ba4714df5a9845b">m_subgraphId</a> = id; }</span></span></div>

</div>


Reference <a href="#afa257c0a638d14c60ba4714df5a9845b">m\_subgraphId</a>.
</div>
</div>

### subgraphId() {#a946942fcd286a1fa51650603fa75b89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::subgraphId ()</td>
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



Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a946942fcd286a1fa51650603fa75b89a">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afa257c0a638d14c60ba4714df5a9845b">m_subgraphId</a>; }</span></span></div>

</div>


Reference <a href="#afa257c0a638d14c60ba4714df5a9845b">m\_subgraphId</a>.

Referenced by <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>.
</div>
</div>

### write() {#a261123fa5550fbc2dd3b146e18f9f221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::write (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> f, bool topDown, bool toChildren, bool backArrows)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 655 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a261123fa5550fbc2dd3b146e18f9f221">655</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a261123fa5550fbc2dd3b146e18f9f221">DotNode::write</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> format,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> topDown,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> toChildren,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> backArrows)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DotNode::write(%d) name=%s this=%p written=%d visible=%d\n",m_distance,qPrint(m_label),this,m_written,m_visible);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// node already written to the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ab092b4fec02c4420c518ad325cc4b175">m_visible</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// node is not visible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>(t,gt,format,<a href="#a408a1095014b55475e7138d861597b69">m_truncated</a>==<a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (toChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cn : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cn-&gt;isVisible())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("write arrow %s%s%s\n",qPrint(label()),backArrows?"&lt;-":"-&gt;",qPrint(cn-&gt;label()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>(t,gt,format,cn,&amp;(*it),topDown,backArrows);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      cn-&gt;write(t,gt,format,topDown,toChildren,backArrows);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// render parents</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pn : <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pn-&gt;isVisible())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a> = pn-&gt;children();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> child_it = std::find(<a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>.begin(),<a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>.end(),</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index = child_it - <a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("write arrow %s%s%s\n",qPrint(label()),backArrows?"&lt;-":"-&gt;",qPrint(pn-&gt;label()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>(t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">          gt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">          format,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">          pn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">          &amp;pn-&gt;edgeInfo()[index],</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">          backArrows</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">        );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      pn-&gt;write(t,gt,format,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,backArrows);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("end DotNode::write(%d) name=%s\n",distance,qPrint(m_label));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>, <a href="#aa397d81f5f600725c2a98d77e3f27908">m\_parents</a>, <a href="#a408a1095014b55475e7138d861597b69">m\_truncated</a>, <a href="#ab092b4fec02c4420c518ad325cc4b175">m\_visible</a>, <a href="#a53c2882a93930d9fc813d4e6152aa475">m\_written</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a>, <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a> and <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>.
</div>
</div>

### writeArrow() {#aeb01acd1ef9dbeb87e35e7eae24143b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeArrow (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> f, const <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * cn, const <a href="/web-doxygen/docs/api/classes/edgeinfo">EdgeInfo</a> * ei, bool topDown, bool pointBack=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 604 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">604</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">DotNode::writeArrow</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> </span><span class="doxyHighlightComment">/* format */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *cn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo">EdgeInfo</a> *ei,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> topDown,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pointBack)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (topDown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; cn-&gt;<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" -&gt; Node"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (topDown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; cn-&gt;<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" ["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/edgeproperties">EdgeProperties</a> *eProps = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(UML_LOOK) ? &amp;<a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a7bcfb1cbfe72252acb0e3c103189c105">umlEdgeProps</a> : &amp;<a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a0fbb1be142f0fa3995ad058c3e34a47b">normalEdgeProps</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> aStyle = eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#a2b2315fe38a4822f4e657c71236fb027">arrowStyleMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">color</a>()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> umlUseArrow = aStyle==</span><span class="doxyHighlightStringLiteral">"odiamond"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id=\"edge"</span><span class="doxyHighlight"> &lt;&lt; <a href="#aeb54967e727ba0255965c24265cfb376">m_graph</a>-&gt;getNextEdgeNumber() &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightStringLiteral">"_Node"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%06d"</span><span class="doxyHighlight">,<a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>) &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightStringLiteral">"_Node"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%06d"</span><span class="doxyHighlight">,cn-&gt;<a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pointBack &amp;&amp; !umlUseArrow) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"dir=\"back\","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"color=\""</span><span class="doxyHighlight"> &lt;&lt; eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#ad0c9d3fa5e49b41e92ff95cbf188a5b1">edgeColorMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">color</a>()] &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"style=\""</span><span class="doxyHighlight"> &lt;&lt; eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#a7938928bf27311c0e4acf2c40e0f0510">edgeStyleMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a534c4e3b34bb87d6077fc1cb398dd121">style</a>()] &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",tooltip=\" \""</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// space in tooltip is required otherwise still something like 'Node0 -&gt; Node1' is used</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#abeb235190964a4b359ff9dc1970fb327">label</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",label="</span><span class="doxyHighlight"> &lt;&lt; <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>(ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#abeb235190964a4b359ff9dc1970fb327">label</a>(),<a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">LabelStyle::Table</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" ,fontcolor=\"grey\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(UML_LOOK) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">    eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#a2b2315fe38a4822f4e657c71236fb027">arrowStyleMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">color</a>()] &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">    (gt==<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">GraphType::Inheritance</a> || gt==<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">GraphType::Collaboration</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> rev = pointBack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (umlUseArrow) rev=!rev; </span><span class="doxyHighlightComment">// UML use relates has arrow on the start side</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rev)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",arrowtail=\""</span><span class="doxyHighlight"> &lt;&lt; eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#a2b2315fe38a4822f4e657c71236fb027">arrowStyleMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">color</a>()] &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",arrowhead=\""</span><span class="doxyHighlight"> &lt;&lt; eProps-&gt;<a href="/web-doxygen/docs/api/structs/edgeproperties/#a2b2315fe38a4822f4e657c71236fb027">arrowStyleMap</a>[ei-&gt;<a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">color</a>()] &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/edgeproperties/#a2b2315fe38a4822f4e657c71236fb027">EdgeProperties::arrowStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">Collaboration</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a9aa86c737a1f46a55567ee172b5a07c9">EdgeInfo::color</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>, <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="/web-doxygen/docs/api/structs/edgeproperties/#ad0c9d3fa5e49b41e92ff95cbf188a5b1">EdgeProperties::edgeColorMap</a>, <a href="/web-doxygen/docs/api/structs/edgeproperties/#a7938928bf27311c0e4acf2c40e0f0510">EdgeProperties::edgeStyleMap</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">Inheritance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#abeb235190964a4b359ff9dc1970fb327">EdgeInfo::label</a>, <a href="#aeb54967e727ba0255965c24265cfb376">m\_graph</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a0fbb1be142f0fa3995ad058c3e34a47b">normalEdgeProps</a>, <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a534c4e3b34bb87d6077fc1cb398dd121">EdgeInfo::style</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">Table</a> and <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a7bcfb1cbfe72252acb0e3c103189c105">umlEdgeProps</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a> and <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

### writeBox() {#a3f65f51eefb97cf188587b56115d973a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeBox (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> f, bool hasNonReachableChildren)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 540 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f65f51eefb97cf188587b56115d973a">540</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3f65f51eefb97cf188587b56115d973a">DotNode::writeBox</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> </span><span class="doxyHighlightComment">/*format*/</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasNonReachableChildren)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *labCol = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fillCol = </span><span class="doxyHighlightStringLiteral">"white"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;hasDocumentation() &amp;&amp; hasNonReachableChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      labCol = </span><span class="doxyHighlightStringLiteral">"red"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      fillCol = </span><span class="doxyHighlightStringLiteral">"#FFF0F0"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;hasDocumentation() &amp;&amp; !hasNonReachableChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      labCol = </span><span class="doxyHighlightStringLiteral">"gray40"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;hasDocumentation() &amp;&amp; hasNonReachableChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      labCol = </span><span class="doxyHighlightStringLiteral">"orangered"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// (!m_classDef-&gt;hasDocumentation() &amp;&amp; !hasNonReachableChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">      labCol = </span><span class="doxyHighlightStringLiteral">"grey75"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;templateMaster() &amp;&amp; <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;isImplicitTemplateInstance() &amp;&amp; <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;templateMaster()-&gt;hasDocumentation())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">        labCol = </span><span class="doxyHighlightStringLiteral">"gray40"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    labCol = <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty() ? </span><span class="doxyHighlightStringLiteral">"grey60"</span><span class="doxyHighlight"> :  </span><span class="doxyHighlightComment">// non link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">    (hasNonReachableChildren ? </span><span class="doxyHighlightStringLiteral">"red"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"grey40"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    fillCol = <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty() ? </span><span class="doxyHighlightStringLiteral">"#E0E0E0"</span><span class="doxyHighlight"> :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">    (hasNonReachableChildren ? </span><span class="doxyHighlightStringLiteral">"#FFF0F0"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"white"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" ["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id=\"Node"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%06d"</span><span class="doxyHighlight">,<a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a>(t,gt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",height=0.2,width=0.4"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m_isRoot</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",color=\"gray40\", fillcolor=\"grey60\", style=\"filled\", fontcolor=\"black\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",color=\""</span><span class="doxyHighlight"> &lt;&lt; labCol &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">", fillcolor=\""</span><span class="doxyHighlight"> &lt;&lt; fillCol &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">", style=\"filled\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1cb314bd0d605efa7019319e3da26870">writeUrl</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a1cd471e954ba6e4bdd9060787da53286">m_tooltip</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",tooltip=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>(<a href="#a1cd471e954ba6e4bdd9060787da53286">m_tooltip</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",tooltip=\" \""</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// space in tooltip is required otherwise still something like 'Node0' is used</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>, <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m\_classDef</a>, <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m\_isRoot</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#a1cd471e954ba6e4bdd9060787da53286">m\_tooltip</a>, <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a> and <a href="#a1cb314bd0d605efa7019319e3da26870">writeUrl</a>.

Referenced by <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

### writeDEF() {#a0332e2befe926de95b367c391a0ac70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeDEF (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 831 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0332e2befe926de95b367c391a0ac70c">831</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0332e2befe926de95b367c391a0ac70c">DotNode::writeDEF</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* nodePrefix = </span><span class="doxyHighlightStringLiteral">"        node-"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      node = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; nodePrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"id    = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; nodePrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label = '"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url(<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dollarPos = url.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; nodePrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"link = {\n"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; nodePrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"link-id = '"</span><span class="doxyHighlight"> &lt;&lt; url.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(dollarPos+1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> &lt;&lt; nodePrefix &lt;&lt; </span><span class="doxyHighlightStringLiteral">"link-external = '"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; url.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(dollarPos) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        };\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;childNode : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo">EdgeInfo</a> &amp;<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        node-child = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          child-id = '"</span><span class="doxyHighlight"> &lt;&lt; childNode-&gt;number() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          relation = "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.color())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>:    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"public-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>:   t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"protected-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>:     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"private-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"usage"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"template-instance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type-constraint"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>:    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          edgelabel = &lt;&lt;_EnD_oF_dEf_TeXt_\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; <a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_EnD_oF_dEf_TeXt_;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        }; /* node-child */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">    ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      }; /* node */\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>, <a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a> and <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>.
</div>
</div>

### writeDocbook() {#a4be56bbbeefd5d44b58d28f05c446725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeDocbook (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool isClassGraph)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 768 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4be56bbbeefd5d44b58d28f05c446725">768</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4be56bbbeefd5d44b58d28f05c446725">DotNode::writeDocbook</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isClassGraph)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;node id=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;label&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/label&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url(<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dollarPos = url.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;link refid=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(url.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(dollarPos+1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" external=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(url.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(dollarPos)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;childNode : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo">EdgeInfo</a> &amp;<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;childnode refid=\""</span><span class="doxyHighlight"> &lt;&lt; childNode-&gt;number() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" relation=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isClassGraph)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.color())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>:    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"public-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>:   t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"protected-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>:     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"private-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"usage"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"template-instance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type-constraint"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>:    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// include graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"include"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ni=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((ni=<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().find(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;edgelabel&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().mid(p,ni-p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/edgelabel&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">        p=ni+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;edgelabel&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().right(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().length()-p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/edgelabel&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/childnode&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">    ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a> and <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>.
</div>
</div>

### writeLabel() {#ae7a5c86a2927e880a7c8413e57275811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeLabel (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 415 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7a5c86a2927e880a7c8413e57275811">415</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae7a5c86a2927e880a7c8413e57275811">DotNode::writeLabel</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72">GraphType</a> gt)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(UML_LOOK) &amp;&amp; (gt==<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">GraphType::Inheritance</a> || gt==<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">GraphType::Collaboration</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Set shape to the plain type.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// the UML properties and methods are rendered using dot' HTML like table format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"shape=plain,label="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add names shown as relations to a set, so we don't show</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// them as attributes as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> arrowNames;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// for each edge</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ei : <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ei.label().isEmpty()) </span><span class="doxyHighlightComment">// labels joined by \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lab;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=ei.label().find(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">          lab = <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#aad3d1cd78282b91d3a5d5c91686cb13b">stripProtectionPrefix</a>(ei.label().mid(p,i-p));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">          arrowNames.insert(lab.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">          p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">        lab = <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#aad3d1cd78282b91d3a5d5c91686cb13b">stripProtectionPrefix</a>(ei.label().right(ei.label().length()-p));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">        arrowNames.insert(lab.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> hr_start = </span><span class="doxyHighlightStringLiteral">"&lt;TR&gt;&lt;TD COLSPAN=\"2\" CELLPADDING=\"1\" CELLSPACING=\"0\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> hr_end = </span><span class="doxyHighlightStringLiteral">"&lt;/TD&gt;&lt;/TR&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> sep = </span><span class="doxyHighlightStringLiteral">"&lt;HR/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> empty_line = </span><span class="doxyHighlightStringLiteral">"&lt;TR&gt;&lt;TD COLSPAN=\"2\" CELLPADDING=\"1\" CELLSPACING=\"0\"&gt;&amp;nbsp;&lt;/TD&gt;&lt;/TR&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("DotNode::writeBox for %s\n",qPrint(m_classDef-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;&lt;TABLE CELLBORDER=\"0\" BORDER=\"1\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; hr_start &lt;&lt; <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>,<a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">LabelStyle::List</a>) &lt;&lt; hr_end;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> dotUmlDetails = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(DOT_UML_DETAILS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dotUmlDetails!=DOT_UML_DETAILS_t::NONE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> lineWritten = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; sep;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PubAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PubStaticAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::Properties()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PacAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PacStaticAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::ProAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::ProStaticAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTRACT_PRIVATE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PriAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PriStaticAttribs()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lineWritten) t &lt;&lt; empty_line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; sep;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      lineWritten = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PubMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PubStaticMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PubSlots()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PacMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PacStaticMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::ProMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::ProStaticMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::ProSlots()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTRACT_PRIVATE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PriMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PriStaticMethods()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">,<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberList(MemberListType::PriSlots()),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getLanguage()!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>-&gt;getMemberGroups())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mg-&gt;members().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>(t,</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">,&amp;mg-&gt;members(),<a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>,lineWritten,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;arrowNames);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lineWritten) t &lt;&lt; empty_line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/TABLE&gt;&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOT_NODE_ATTR).contains(</span><span class="doxyHighlightStringLiteral">"shape=plain"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m_isRoot</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;&lt;b&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt;&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a408a1095014b55475e7138d861597b69">m_truncated</a> == <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;&lt;i&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/i&gt;&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &lt;&lt; <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>,<a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">LabelStyle::Plain</a>) &lt;&lt; </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// standard look</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label="</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &lt;&lt; <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>,<a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">LabelStyle::Plain</a>) &lt;&lt; </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">Collaboration</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="#a6bc845933b52f07e32502d844a9b2794">convertLabel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">Inheritance</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">List</a>, <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m\_classDef</a>, <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>, <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m\_isRoot</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a408a1095014b55475e7138d861597b69">m\_truncated</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">Plain</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#aad3d1cd78282b91d3a5d5c91686cb13b">stripProtectionPrefix</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ac40de94762a7659599b2056942373102a4bb6a5a03b3707d0819d9c4023b516cd">Truncated</a> and <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>.

Referenced by <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>.
</div>
</div>

### writeUrl() {#a1cb314bd0d605efa7019319e3da26870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeUrl (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 515 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cb314bd0d605efa7019319e3da26870">515</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1cb314bd0d605efa7019319e3da26870">DotNode::writeUrl</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty() || <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a> == <a href="#ad1c9b1e1192faac2bf956a6a3043be0c">DotNode::placeholderUrl</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tagPos = <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.findRev(</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",URL=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> noTagURL = <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.left(tagPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    noTagURL = <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.mid(tagPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> anchorPos = noTagURL.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (anchorPos==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(noTagURL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; noTagURL &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// insert extensiom before anchor</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = noTagURL.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(anchorPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; fn &lt;&lt; noTagURL.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(noTagURL.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - anchorPos) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>, <a href="#ad1c9b1e1192faac2bf956a6a3043be0c">placeholderUrl</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>.

Referenced by <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>.
</div>
</div>

### writeXML() {#aed2051e58bce93b9250b99108a77ae00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::writeXML (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool isClassGraph)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 706 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed2051e58bce93b9250b99108a77ae00">706</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aed2051e58bce93b9250b99108a77ae00">DotNode::writeXML</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isClassGraph)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;node id=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;label&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/label&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url(<a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dollarPos = url.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;link refid=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(url.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(dollarPos+1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dollarPos&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" external=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(url.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(dollarPos)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;childNode : <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo">EdgeInfo</a> &amp;<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;childnode refid=\""</span><span class="doxyHighlight"> &lt;&lt; childNode-&gt;number() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" relation=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isClassGraph)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.color())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>:    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"public-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>:   t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"protected-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>:     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"private-inheritance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"usage"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"template-instance"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type-constraint"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>:    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// include graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"include"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ni=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((ni=<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().find(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;edgelabel&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().mid(p,ni-p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/edgelabel&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">        p=ni+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;edgelabel&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().right(<a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>.label().length()-p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/edgelabel&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/childnode&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/node&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4a29d1be23ca8384e036227c0d375949">EdgeInfo::Green</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228aa5653e1b61f6d5bf0b762fa8887aaec6">EdgeInfo::Grey</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#ac1234b87999769323c75747182e7b9d1">m\_children</a>, <a href="#a761040a5361299f900b49c35c2462382">m\_edgeInfo</a>, <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m\_label</a>, <a href="#a13b1afa66e70ead8d342df1305cc8297">m\_number</a>, <a href="#afeafe76686b1e932aacbd7e9e854ff26">m\_url</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a5dd85875507d2ff6d9aa5ae31ac0ae02">EdgeInfo::Orange</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a546d073d42055e46bd7922bb551ca3d3">EdgeInfo::Orange2</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228a4f78453f5006dccb5ecea6bd6ae41a98">EdgeInfo::Purple</a> and <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ac4f6ba2f7702235368f07ff81f6b0c74">EdgeInfo::Red</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_children {#ac1234b87999769323c75747182e7b9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeRefVector DotNode::m_children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

list of child nodes (outgoing arrows)

Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1234b87999769323c75747182e7b9d1">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> <a href="#ac1234b87999769323c75747182e7b9d1">m_children</a>;             </span><span class="doxyHighlightComment">//!&lt; list of child nodes (outgoing arrows)</span></span></div>

</div>


Referenced by <a href="#ac54555a412724c31181a40a50213e38e">addChild</a>, <a href="#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>, <a href="#a27692f33c86a577ad85ab7176539d4de">clearWriteFlag</a>, <a href="#abb8eb3aaf830fe2685ebc36bf783857a">colorConnectedNodes</a>, <a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a>, <a href="#a62686e145c94129d85409214fb3e0571">removeChild</a>, <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>, <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>, <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### m\_classDef {#acad63761d0fcce398f2d8a663fd1cfa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef* DotNode::m_classDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

class representing this node (can be 0)

Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acad63761d0fcce398f2d8a663fd1cfa8">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * <a href="#acad63761d0fcce398f2d8a663fd1cfa8">m_classDef</a>;             </span><span class="doxyHighlightComment">//!&lt; class representing this node (can be 0)</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a> and <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a>.
</div>
</div>

### m\_deleted {#ae08bcf1483374985a785829e702b4f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_deleted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

used to mark a node as deleted

Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae08bcf1483374985a785829e702b4f0d">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#ae08bcf1483374985a785829e702b4f0d">m_deleted</a>    = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">//!&lt; used to mark a node as deleted</span></span></div>

</div>


Referenced by <a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a>.
</div>
</div>

### m\_distance {#a7792be9d15ff8fc45863bce185e3e328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::m_distance = 1000</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

shortest path to the root node

Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7792be9d15ff8fc45863bce185e3e328">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">              <a href="#a7792be9d15ff8fc45863bce185e3e328">m_distance</a>   = 1000;    </span><span class="doxyHighlightComment">//!&lt; shortest path to the root node</span></span></div>

</div>


Referenced by <a href="#a196e6efc147272506e3e0564dfe47bfe">distance</a> and <a href="#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>.
</div>
</div>

### m\_edgeInfo {#a761040a5361299f900b49c35c2462382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeInfoVector DotNode::m_edgeInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

edge info for each child

Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a761040a5361299f900b49c35c2462382">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a27cb2e97ee7dd89763d1e5ee7f936324">EdgeInfoVector</a>   <a href="#a761040a5361299f900b49c35c2462382">m_edgeInfo</a>;             </span><span class="doxyHighlightComment">//!&lt; edge info for each child</span></span></div>

</div>


Referenced by <a href="#ac54555a412724c31181a40a50213e38e">addChild</a>, <a href="#a323a0f1b9913242153ef1f84abb05a60">edgeInfo</a>, <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>, <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a>, <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### m\_graph {#aeb54967e727ba0255965c24265cfb376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGraph* DotNode::m_graph</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb54967e727ba0255965c24265cfb376">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a>        *<a href="#aeb54967e727ba0255965c24265cfb376">m_graph</a>;</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>.
</div>
</div>

### m\_hasDoc {#a3911b863e988573b48bd22cb81c49829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_hasDoc = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

used to mark a node as documented

Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3911b863e988573b48bd22cb81c49829">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#a3911b863e988573b48bd22cb81c49829">m_hasDoc</a>     = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">//!&lt; used to mark a node as documented</span></span></div>

</div>


Referenced by <a href="#ac192b74541fe778106f8c17e970dc489">hasDocumentation</a> and <a href="#a92bc5bd51995cf7afba4f94f895e0ce7">markHasDocumentation</a>.
</div>
</div>

### m\_isRoot {#a2653bd0cf33ae9b2c8ede6a00df5fa8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_isRoot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

indicates if this is a root node

Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#a2653bd0cf33ae9b2c8ede6a00df5fa8e">m_isRoot</a>;               </span><span class="doxyHighlightComment">//!&lt; indicates if this is a root node</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a> and <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a>.
</div>
</div>

### m\_label {#a2e5b698b3f8e557561cf25e7b523ebc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotNode::m_label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

label text

Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e5b698b3f8e557561cf25e7b523ebc9">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#a2e5b698b3f8e557561cf25e7b523ebc9">m_label</a>;                </span><span class="doxyHighlightComment">//!&lt; label text</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#aead1705f4e6586bd7ba613fdda2e7241">label</a>, <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>, <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a>, <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### m\_number {#a13b1afa66e70ead8d342df1305cc8297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::m_number</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13b1afa66e70ead8d342df1305cc8297">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">              <a href="#a13b1afa66e70ead8d342df1305cc8297">m_number</a>;</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a3c08a5ee367bbf4c58c719ff7f8e0fc7">number</a>, <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a>, <a href="#ae1dc99d158ddb9a5ce63dda67ea843f5">setNodeId</a>, <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>, <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>, <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### m\_parents {#aa397d81f5f600725c2a98d77e3f27908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeRefVector DotNode::m_parents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

list of parent nodes (incoming arrows)

Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa397d81f5f600725c2a98d77e3f27908">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> <a href="#aa397d81f5f600725c2a98d77e3f27908">m_parents</a>;              </span><span class="doxyHighlightComment">//!&lt; list of parent nodes (incoming arrows)</span></span></div>

</div>


Referenced by <a href="#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>, <a href="#a27692f33c86a577ad85ab7176539d4de">clearWriteFlag</a>, <a href="#abb8eb3aaf830fe2685ebc36bf783857a">colorConnectedNodes</a>, <a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a>, <a href="#a05f42851921caf9442ed2c4e4468b695">findParent</a>, <a href="#aca9b5bf9d87bd3f71d4e7d1e6f8c6239">parents</a>, <a href="#a2a36f34067293e7428ae7ea527678fee">removeParent</a>, <a href="#a4e9da1f53e500d73aa8997ead79093fb">renumberNodes</a> and <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

### m\_renumbered {#a8debf620e1d23ba12a2255d7ff7b8d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_renumbered = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

indicates if the node has been renumbered (to prevent endless loops)

Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8debf620e1d23ba12a2255d7ff7b8d32">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#a8debf620e1d23ba12a2255d7ff7b8d32">m_renumbered</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">//!&lt; indicates if the node has been renumbered (to prevent endless loops)</span></span></div>

</div>


Referenced by <a href="#a778848585e3ab3d63610f568c7299511">isRenumbered</a> and <a href="#a1d245f9612e50c197d2df5392bfae2bb">markRenumbered</a>.
</div>
</div>

### m\_subgraphId {#afa257c0a638d14c60ba4714df5a9845b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotNode::m_subgraphId = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa257c0a638d14c60ba4714df5a9845b">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">              <a href="#afa257c0a638d14c60ba4714df5a9845b">m_subgraphId</a> = -1;</span></span></div>

</div>


Referenced by <a href="#a54523891e16f0ad2c98f745983f0ed1c">setSubgraphId</a> and <a href="#a946942fcd286a1fa51650603fa75b89a">subgraphId</a>.
</div>
</div>

### m\_tooltip {#a1cd471e954ba6e4bdd9060787da53286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotNode::m_tooltip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

node's tooltip

Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cd471e954ba6e4bdd9060787da53286">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#a1cd471e954ba6e4bdd9060787da53286">m_tooltip</a>;              </span><span class="doxyHighlightComment">//!&lt; node's tooltip</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> and <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>.
</div>
</div>

### m\_truncated {#a408a1095014b55475e7138d861597b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TruncState DotNode::m_truncated = <a href="#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

does the node have non-visible children/parents

Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a408a1095014b55475e7138d861597b69">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac40de94762a7659599b2056942373102">TruncState</a>       <a href="#a408a1095014b55475e7138d861597b69">m_truncated</a>  = <a href="#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">Unknown</a>; </span><span class="doxyHighlightComment">//!&lt; does the node have non-visible children/parents</span></span></div>

</div>


Referenced by <a href="#adcfb83215c88dcdd5c39391547e3882b">isTruncated</a>, <a href="#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a>, <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a> and <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a>.
</div>
</div>

### m\_url {#afeafe76686b1e932aacbd7e9e854ff26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotNode::m_url</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

url of the node (format: remote$local)

Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afeafe76686b1e932aacbd7e9e854ff26">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#afeafe76686b1e932aacbd7e9e854ff26">m_url</a>;                  </span><span class="doxyHighlightComment">//!&lt; url of the node (format: remote$local)</span></span></div>

</div>


Referenced by <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>, <a href="#a3f65f51eefb97cf188587b56115d973a">writeBox</a>, <a href="#a0332e2befe926de95b367c391a0ac70c">writeDEF</a>, <a href="#a4be56bbbeefd5d44b58d28f05c446725">writeDocbook</a>, <a href="#a1cb314bd0d605efa7019319e3da26870">writeUrl</a> and <a href="#aed2051e58bce93b9250b99108a77ae00">writeXML</a>.
</div>
</div>

### m\_visible {#ab092b4fec02c4420c518ad325cc4b175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_visible = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

is the node visible in the output

Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab092b4fec02c4420c518ad325cc4b175">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#ab092b4fec02c4420c518ad325cc4b175">m_visible</a>    = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">//!&lt; is the node visible in the output</span></span></div>

</div>


Referenced by <a href="#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>, <a href="#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a> and <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

### m\_written {#a53c2882a93930d9fc813d4e6152aa475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotNode::m_written = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

used to mark a node as written

Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53c2882a93930d9fc813d4e6152aa475">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             <a href="#a53c2882a93930d9fc813d4e6152aa475">m_written</a>    = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;   </span><span class="doxyHighlightComment">//!&lt; used to mark a node as written</span></span></div>

</div>


Referenced by <a href="#a27692f33c86a577ad85ab7176539d4de">clearWriteFlag</a>, <a href="#aa09c516ca773d02f6af1536df5d47498">isWritten</a> and <a href="#a261123fa5550fbc2dd3b146e18f9f221">write</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### convertLabel() {#a6bc845933b52f07e32502d844a9b2794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotNode::convertLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, <a href="#acd975dffca58fc0d6bbcae4b37e280ed">LabelStyle</a> style=<a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">LabelStyle::Plain</a>)</td>
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



Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bc845933b52f07e32502d844a9b2794">196</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l, <a href="#acd975dffca58fc0d6bbcae4b37e280ed">LabelStyle</a> style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bBefore(</span><span class="doxyHighlightStringLiteral">"\\_/&lt;({[: =-+@%#~?$"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// break before character set</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bAfter(</span><span class="doxyHighlightStringLiteral">"&gt;]),:;|"</span><span class="doxyHighlight">);              </span><span class="doxyHighlightComment">// break after  character set</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> p(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t idx = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> charsLeft=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(p.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sinceLast=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> foldLen = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_WRAP_THRESHOLD); </span><span class="doxyHighlightComment">// ideal text length</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> br;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> br1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">LabelStyle::Table</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    result += </span><span class="doxyHighlightStringLiteral">"&lt;&lt;TABLE CELLBORDER=\"0\" BORDER=\"0\"&gt;&lt;TR&gt;&lt;TD VALIGN=\"top\" ALIGN=\"LEFT\" CELLPADDING=\"1\" CELLSPACING=\"0\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">LabelStyle::List</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    br = </span><span class="doxyHighlightStringLiteral">"&lt;BR ALIGN=\"LEFT\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">LabelStyle::Table</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    br1 = </span><span class="doxyHighlightStringLiteral">"&lt;/TD&gt;&lt;/TR&gt;\n&lt;TR&gt;&lt;TD VALIGN=\"top\" ALIGN=\"LEFT\" CELLPADDING=\"1\" CELLSPACING=\"0\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    br = br1 + </span><span class="doxyHighlightStringLiteral">"&amp;nbsp;&amp;nbsp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// style==LabelStyle::Plain</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">    br = </span><span class="doxyHighlightStringLiteral">"\\l"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (idx &lt; p.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = p[idx++];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2] = { c, 0 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *replacement = cs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style!=<a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">LabelStyle::Plain</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: replacement=</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: replacement=</span><span class="doxyHighlightStringLiteral">"\\n"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: replacement=</span><span class="doxyHighlightStringLiteral">"&amp;apos;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// style==LabelStyle::Plain</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: replacement=</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: replacement=</span><span class="doxyHighlightStringLiteral">"\\n"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\&lt;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\&gt;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\|"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\{"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:  replacement=</span><span class="doxyHighlightStringLiteral">"\\}"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Some heuristics to insert newlines to prevent too long</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// boxes and at the same time prevent ugly breaks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">LabelStyle::Table</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=br1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">      foldLen = (3*foldLen+sinceLast+2)/4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      sinceLast=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((pc!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> || c!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) &amp;&amp; charsLeft&gt;foldLen/3 &amp;&amp; sinceLast&gt;foldLen &amp;&amp; bBefore.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(c))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=br;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      foldLen = (foldLen+sinceLast+1)/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      sinceLast=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (charsLeft&gt;1+foldLen/4 &amp;&amp; sinceLast&gt;foldLen+foldLen/3 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      !isupper(c) &amp;&amp; isupper(p[idx]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=br;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      foldLen = (foldLen+sinceLast+1)/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      sinceLast=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (charsLeft&gt;foldLen/3 &amp;&amp; sinceLast&gt;foldLen &amp;&amp; bAfter.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(c) &amp;&amp; (c!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> || p[idx]!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=br;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">      foldLen = (foldLen+sinceLast+1)/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      sinceLast=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      sinceLast++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    charsLeft--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">LabelStyle::List</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">     result = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (style==<a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">LabelStyle::Table</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">    result += </span><span class="doxyHighlightStringLiteral">"&lt;/TD&gt;&lt;/TR&gt;\n&lt;/TABLE&gt;&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda4ee29ca12c7d126654bd0e5275de6135">List</a>, <a href="#acd975dffca58fc0d6bbcae4b37e280eda4cd8413207629a963225f4314b53adcd">Plain</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="#acd975dffca58fc0d6bbcae4b37e280eda51c45b795d5d18a3e4e0c37e8b20a141">Table</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>, <a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge/#a1f4c832d9b0e56ecdf8f164784623354">DotGroupCollaboration::Edge::write</a>, <a href="#aeb01acd1ef9dbeb87e35e7eae24143b1">writeArrow</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a> and <a href="#ae7a5c86a2927e880a7c8413e57275811">writeLabel</a>.
</div>
</div>

### deleteNodes() {#a748649462fd72baa804eccd77fcfa612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotNode::deleteNodes (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * node)</td>
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




helper function that deletes all nodes in a connected graph, given one of the graph's nodes

Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>, definition at line 405 of file <a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a748649462fd72baa804eccd77fcfa612">405</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a748649462fd72baa804eccd77fcfa612">DotNode::deleteNodes</a>(<a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a> *node)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dotnode-h/#a02164da1f68d5136eafe9274101e374a">DotNodeRefVector</a> deletedNodes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  node-&gt;<a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a>(deletedNodes); </span><span class="doxyHighlightComment">// collect nodes to be deleted.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dotNode : deletedNodes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> dotNode;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ae2c044edad92d6008b036ae6c1f97551">deleteNode</a> and <a href="#a48f504e2687c7ccf1f010ab9a1aeebf3">DotNode</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a3a3d80fa9ab081c5458268636796bfbc">DotCallGraph::\~DotCallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a7cfd0c424567809bb652f0d952f85272">DotClassGraph::\~DotClassGraph</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#af16036a50c08251c90de8841af69858a">DotInclDepGraph::\~DotInclDepGraph</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### placeholderUrl {#ad1c9b1e1192faac2bf956a6a3043be0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto DotNode::placeholderUrl = "-"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1c9b1e1192faac2bf956a6a3043be0c">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#ad1c9b1e1192faac2bf956a6a3043be0c">placeholderUrl</a> = </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/dotlegendgraph/#af02bfaa220696e0722080995d191d001">DotLegendGraph::computeTheGraph</a> and <a href="#a1cb314bd0d605efa7019319e3da26870">writeUrl</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotnode-cpp">dotnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
