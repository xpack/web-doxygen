---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/grouping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Grouping




<p>Doxygen has three mechanisms to group things together. One mechanism works at a global level, creating a new page for each group. These groups are called <a href="#topics">'topics'</a> in the documentation. The second mechanism works within a member list of some compound entity, and is referred to as a <a href="#memgroup">'member groups'</a>. For <a href="/web-doxygen/docs/pages/commands/#cmdpage">pages</a> there is a third grouping mechanism referred to as <a href="#subpaging">Subpaging</a>.</p>


## Topics {#topics}


<p>Grouping is a way to group things together on a separate page, called a topic. You can document a group as a whole, as well as all individual members. Members of a group can be files, namespaces, classes, concepts, modules, functions, variables, enums, typedefs, and defines, but also other groups.</p>


<p>To define a group, you should put the <a href="/web-doxygen/docs/pages/commands/#cmddefgroup">\defgroup</a> command in a special comment block. The first argument of the command is a label that should uniquely identify the group. The second argument is the name or title of the group as it should appear in the documentation.</p>


<p>You can make an entity a member of a specific group by putting a <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a> command inside its documentation block.</p>


<p>To avoid putting <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a> commands in the documentation for each member you can also group members together by the open marker <span class="doxyComputerOutput">@{</span> before the group and the closing marker <span class="doxyComputerOutput">@}</span> after the group. The markers can be put in the documentation of the group definition or in a separate documentation block.</p>


<p>Groups themselves can also be nested using these grouping markers.</p>


<p>You will get an error message when you use the same group label more than once. If you don't want Doxygen to enforce unique labels, then you can use <a href="/web-doxygen/docs/pages/commands/#cmdaddtogroup">\addtogroup</a> instead of <a href="/web-doxygen/docs/pages/commands/#cmddefgroup">\defgroup</a>. It can be used exactly like <a href="/web-doxygen/docs/pages/commands/#cmddefgroup">\defgroup</a>, but when the group has been defined already, then it silently merges the existing documentation with the new one. The title of the group is optional for this command, so you can use</p>



<pre><code>/** \addtogroup &lt;label&gt;
 *  @{
 */
...

/** @}*/
</code></pre>


<p>to add additional members to a group that is defined in more detail elsewhere.</p>


<p>Note that compound entities (like classes, files and namespaces) can be put into multiple groups, but members (like variable, functions, typedefs and enums) can only be a member of one group (this restriction is in place to avoid ambiguous linking targets in case a member is not documented in the context of its class, namespace or file, but only visible as part of a group).</p>


<p>Doxygen will put members into the group whose definition has the highest "priority": e.g. An explicit <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a> overrides an implicit grouping definition via <span class="doxyComputerOutput">@{</span> <span class="doxyComputerOutput">@}</span>. Conflicting grouping definitions with the same priority trigger a warning, unless one definition was for a member without any explicit documentation.</p>


<p>The following example puts VarInA into group A and silently resolves the conflict for IntegerVariable by putting it into group IntVariables, because the second instance of IntegerVariable is undocumented:</p>



<pre><code>/**
 * \ingroup A
 */
extern int VarInA;

/**
 * \defgroup IntVariables Global integer variables
 * @{
 */

/** an integer variable */
extern int IntegerVariable;

/**@}*/

....

/**
 * \defgroup Variables Global variables
 */
/**@{*/

/** a variable in group A */
int VarInA;

int IntegerVariable;

/**@}*/
</code></pre>


<p>The <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a> command can be used to refer to a group. The first argument of the \ref command should be group's label. To use a custom link name, you can put the name of the links in double quotes after the label, as shown by the following example</p>



<pre><code>This is the \ref group_label "link" to this group.
</code></pre>


<p>The priorities of grouping definitions are (from highest to lowest): <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a>, <a href="/web-doxygen/docs/pages/commands/#cmddefgroup">\defgroup</a>, <a href="/web-doxygen/docs/pages/commands/#cmdaddtogroup">\addtogroup</a>, <a href="/web-doxygen/docs/pages/commands/#cmdweakgroup">\weakgroup</a>. The <a href="/web-doxygen/docs/pages/commands/#cmdweakgroup">\weakgroup</a> command is exactly like <a href="/web-doxygen/docs/pages/commands/#cmdaddtogroup">\addtogroup</a> with a lower priority. It was added to allow "lazy" grouping definitions: you can use commands with a higher priority in your .h files to define the hierarchy and <a href="/web-doxygen/docs/pages/commands/#cmdweakgroup">\weakgroup</a> in .c files without having to duplicate the hierarchy exactly.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @defgroup group1 The First Group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  This is the first group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @brief class C1 in group 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C1 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @brief class C2 in group 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C2 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** function in group 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @} */</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// end of group1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @defgroup group2 The Second Group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  This is the second group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @defgroup group3 The Third Group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  This is the third group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @defgroup group4 The Fourth Group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @ingroup group3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Group 4 is a subgroup of group 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @ingroup group2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @brief class C3 in group 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C3 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @ingroup group2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @brief class C4 in group 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C4 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @ingroup group3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @brief class C5 in @link group3 the third group@endlink.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C5 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @ingroup group1 group2 group3 group4</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  namespace N1 is in four groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @sa @link group1 The first group@endlink, group2, group3, group4 </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Also see @ref mypage2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">namespace </span><span class="doxyHighlight">N1 {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @file</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @ingroup group3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @brief this file in group 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @defgroup group5 The Fifth Group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  This is the fifth group</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @page mypage1 This is a section in group 5</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Text of the first section</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @page mypage2 This is another section in group 5</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Text of the second section</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @} */</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// end of group5</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @addtogroup group1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  More documentation for the first group.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** another function in group 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func2() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** yet another function in group 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func3() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @} */</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// end of group1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>
</dd>
</dl>

 
Click <a href="pathname:///examples/group/html/topics.html">here</a>
for the corresponding HTML documentation that is generated by Doxygen.


## Member Groups {#memgroup}


<p>If a compound (e.g. a class or file) has many members, it is often desired to group them together. Doxygen already automatically groups things together on type and protection level, but maybe you feel that this is not enough or that that default grouping is wrong. For instance, because you feel that members of different (syntactic) types belong to the same (semantic) group.</p>


<p>A member group is defined by a</p>



<pre><code>///@{
  ...
///@}
</code></pre>


<p>block or a</p>



<pre><code>/**@{*/
  ...
/**@}*/
</code></pre>


<p>block if you prefer C style comments. Note that the members of the group should be physically inside the member group's body.</p>


<p>Before the opening marker of a block a separate comment block may be placed. This block should contain the <a href="/web-doxygen/docs/pages/commands/#cmdname">@name</a> (or <a href="/web-doxygen/docs/pages/commands/#cmdname">\name</a>) command and is used to specify the header of the group. Optionally, the comment block may also contain more detailed information about the group.</p>


<p>Nesting of member groups is not allowed.</p>


<p>If all members of a member group inside a class have the same type and protection level (for instance all are static public members), then the whole member group is displayed as a subgroup of the type/protection level group (the group is displayed as a subsection of the "Static Public Members" section for instance). If two or more members have different types, then the group is put at the same level as the automatically generated groups. If you want to force all member-groups of a class to be at the top level, you should put a <a href="/web-doxygen/docs/pages/commands/#cmdnosubgrouping">\nosubgrouping</a> command inside the documentation of the class.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** A class. Details */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Memgrp_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    ///@{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Same documentation for both members. Details */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func1InGroup1();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func2InGroup1();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    ///@}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Function without group. Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> ungroupedFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func1InGroup2();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">protected</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> func2InGroup2();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Memgrp_Test::func1InGroup1() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Memgrp_Test::func2InGroup1() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** @name Group2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Description of group 2 </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///@{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Function 2 in group 2 Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Memgrp_Test::func2InGroup2() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Function 1 in group 2 Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Memgrp_Test::func1InGroup2() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///@}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \file </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  docs for this file</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//!@{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//! one description for all members of this group </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//! (because DISTRIBUTE_GROUP_DOC is YES in the config file)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define A 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define B 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> glob_func();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//!@}</span></span></div>

</div>
</dd>
</dl>

 
Click <a href="pathname:///examples/memgrp/html/class_memgrp___test.html">here</a>
for the corresponding HTML documentation that is generated by Doxygen.


<p>Here Group1 is displayed as a subsection of the "Public Members". And Group2 is a separate section because it contains members with different protection levels (i.e. public and protected).</p>


## Subpaging {#subpaging}


<p>Information can be grouped into pages using the <a href="/web-doxygen/docs/pages/commands/#cmdpage">\page</a> and <a href="/web-doxygen/docs/pages/commands/#cmdsubpage">\mainpage</a> commands. Normally, this results in a flat list of pages, where the "main" page is the first in the list.</p>


<p>Instead of adding structure using the approach described in section <a href="#topics">topics</a> it is often more natural and convenient to add additional structure to the pages using the <a href="/web-doxygen/docs/pages/commands/#cmdsubpage">\subpage</a> command.</p>


<p>For a page A the \subpage command adds a link to another page B and at the same time makes page B a subpage of A. This has the effect of making two groups GA and GB, where GB is part of GA, page A is put in group GA, and page B is put in group GB.</p>

 
Go to the <a href="/docs/pages/formulas/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
