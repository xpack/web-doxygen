---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/docblocks
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Documenting the code




<p>This chapter covers two topics:</p>

<ol class="doxyList" type="1">
<li>How to put comments in your code such that Doxygen incorporates them in the documentation it generates. This is further detailed in the <a href="#specialblock">next section</a>.</li>
<li>Ways to structure the contents of a comment block such that the output looks good, as explained in section <a href="#docstructure">Anatomy of a comment block</a>.</li>
</ol>

## Special comment blocks {#specialblock}


<p>A special comment block is a C or C++ style comment block with some additional markings, so Doxygen knows it is a piece of structured text that needs to end up in the generated documentation. The <a href="#cppblock">next</a> section presents the various styles supported by Doxygen.</p>

<p>For Python, VHDL, and Fortran code there are different commenting conventions, which can be found in sections <a href="#pythonblocks">Comment blocks in Python</a>, <a href="#vhdlblocks">Comment blocks in VHDL</a>, and <a href="#fortranblocks">Comment blocks in Fortran</a> respectively.</p>

### Comment blocks for C-like languages (C/C++/C#/Objective-C/PHP/Java) {#cppblock}


<p>For each entity in the code there are two (or in some cases three) types of descriptions, which together form the documentation for that entity; a <em>brief</em> description and <em>detailed</em> description, both are optional. For methods and functions there is also a third type of description, the so called <em>in body</em> description, which consists of the concatenation of all comment blocks found within the body of the method or function.</p>

<p>Having more than one brief or detailed description is allowed (but not recommended, as the order in which the descriptions will appear is not specified).</p>

<p>As the name suggest, a brief description is a short one-liner, whereas the detailed description provides longer, more detailed documentation. An "in body" description can also act as a detailed description or can describe a collection of implementation details. For the HTML output brief descriptions are also used to provide tooltips at places where an item is referenced.</p>

<p>There are several ways to mark a comment block as a detailed description:</p>

<ol class="doxyList" type="1">
<li>You can use the Javadoc style, which consist of a C-style comment block starting with two *'s, like this:

<pre><code>/**
 * ... text ...
 */
</code></pre>

</li>
<li>or you can use the Qt style and add an exclamation mark (!) after the opening of a C-style comment block, as shown in this example:

<pre><code>/*!
 * ... text ...
 */
</code></pre>

In both cases the intermediate *'s are optional, so

<pre><code>/*!
 ... text ...
*/
</code></pre>

is also valid.

</li>
<li>A third alternative is to use a block of <em>at least two</em> C++ comment lines, where each line starts with an additional slash or an exclamation mark. Here are examples of the two cases:

<pre><code>///
/// ... text ...
///
</code></pre>

or

<pre><code>//!
//!... text ...
//!
</code></pre>

Note that a blank line ends a documentation block in this case.

</li>
<li>

Some people like to make their comment blocks more visible in the documentation. For this purpose you can use the following:

<pre><code>/*******************************************//**
 *  ... text
 ***********************************************/
</code></pre>


Note: the 2 slashes to end the normal comment block and start a special comment block.

Note: be careful when using a reformatter like clang-format as it may see this type of comment as 2 separate comments and introduce spacing between them.

or

<pre><code>/////////////////////////////////////////////////
/// ... text ...
/////////////////////////////////////////////////
</code></pre>

or

<pre><code>/***********************************************
 *  ... text
 ***********************************************/
</code></pre>

as long as <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_banner">JAVADOC_BANNER</a> is set to <span class="doxyComputerOutput">YES</span>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A brief history of JavaDoc-style (C-style) comments.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This is the typical JavaDoc-style C-style comment. It starts with two</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * asterisks.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param theory Even if there is only one possible unified theory. it is just a</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *               set of rules and equations.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> cstyle( </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> theory );</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/******************************************************************************</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A brief history of JavaDoc-style (C-style) banner comments.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This is the typical JavaDoc-style C-style "banner" comment. It starts with</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * a forward slash followed by some number, n, of asterisks, where n &gt; 2 It's</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * written this way to be more "visible" to developers who are reading the</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * source code.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Often, developers are unaware that this is not (by default) a valid Doxygen</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * comment block!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * However, as long as JAVADOC_BANNER = YES is added to the Doxyfile, it will</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * work as expected.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This style of commenting behaves well with clang-format.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param theory Even if there is only one possible unified theory. it is just a</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *               set of rules and equations.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> ******************************************************************************/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> javadocBanner( </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> theory );</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**************************************************************************/</span><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A brief history of Doxygen-style banner comments.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This is a Doxygen-style C-style "banner" comment. It starts with a "normal"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * comment and is then converted to a "special" comment block near the end of</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * the first line. It is written this way to be more "visible" to developers</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * who are reading the source code.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This style of commenting behaves poorly with clang-format.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param theory Even if there is only one possible unified theory. it is just a</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *               set of rules and equations.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> ******************************************************************************/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> doxygenBanner( </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> theory );</span></span></div>

</div>

 
 Click <a href="pathname:///examples/javadoc-banner/html/javadoc-banner_8h.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.

</li>
</ol>

<p>For the brief description there are also several possibilities:</p>

<ol class="doxyList" type="1">
<li>One could use the <a href="/web-doxygen/docs/pages/commands/#cmdbrief">\brief</a> command with one of the above comment blocks. This command ends at the end of a paragraph, so the detailed description follows after an empty line.

Here is an example:

<pre><code>/*! \brief Brief description.
 *         Brief description continued.
 *
 *  Detailed description starts here.
 */
</code></pre>

</li>
<li>If <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> is set to <span class="doxyComputerOutput">YES</span> in the configuration file, then using Javadoc style comment blocks will automatically start a brief description which ends at the first dot, question mark or exclamation mark followed by a space or new line. Here is an example:

<pre><code>/** Brief description which ends at this dot. Details follow
 *  here.
 */
</code></pre>


The option has the same effect for multi-line special C++ comments:


<pre><code>/// Brief description which ends at this dot. Details follow
/// here.
</code></pre>

</li>
<li>A third option is to use a special C++ style comment which does not span more than one line. Here are two examples:


<pre><code>/// Brief description.
/** Detailed description. */
</code></pre>

or

<pre><code>//! Brief description.

//! Detailed description
//! starts here.
</code></pre>

Note the blank line in the last example, which is required to separate the brief description from the block containing the detailed description. The <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> should also be set to <span class="doxyComputerOutput">NO</span> for this case.

</li>
</ol>

<p>As you can see Doxygen is quite flexible. If you have multiple detailed descriptions, like in the following example:</p>


<pre><code>//! Brief description, which is
//! really a detailed description since it spans multiple lines.
/*! Another detailed description!
 */
</code></pre>


<p>They will be joined. Note that this is also the case if the descriptions are at different places in the code! In this case the order will depend on the order in which Doxygen parses the code.</p>

<p>Unlike most other documentation systems, Doxygen also allows you to put the documentation of members (including global functions) in front of the <em>definition</em>. This way the documentation can be placed in the source file instead of the header file. This keeps the header file compact, and allows the implementer of the members more direct access to the documentation. As a compromise the brief description could be placed before the declaration and the detailed description before the member definition.</p>

#### Putting documentation after members {#memberdoc}


<p>If you want to document the members of a file, struct, union, class, or enum, it is sometimes desired to place the documentation block after the member instead of before. For this purpose you have to put an additional &lt; marker in the comment block. Note that this also works for the parameters of a function.</p>

<p>Here are some examples:</p>


<pre><code>int var; /*!&lt; Detailed description after the member */
</code></pre>


<p>This block can be used to put a Qt style detailed documentation block <em>after</em> a member. Other ways to do the same are:</p>


<pre><code>int var; /**&lt; Detailed description after the member */
</code></pre>


<p>or</p>


<pre><code>int var; //!&lt; Detailed description after the member
         //!&lt;
</code></pre>


<p>or</p>


<pre><code>int var; ///&lt; Detailed description after the member
         ///&lt;
</code></pre>


<p>Most often one only wants to put a brief description after a member. This is done as follows:</p>


<pre><code>int var; //!&lt; Brief description after the member
</code></pre>


<p>or</p>


<pre><code>int var; ///&lt; Brief description after the member
</code></pre>


<p>For functions one can use the <a href="/web-doxygen/docs/pages/commands/#cmdparam">@param</a> command to document the parameters and then use <span class="doxyComputerOutput">[in]</span>, <span class="doxyComputerOutput">[out]</span>, <span class="doxyComputerOutput">[in,out]</span> to document the direction. For inline documentation this is also possible by starting with the direction attribute, e.g.</p>


<pre><code>void foo(int v /**&lt; [in] docs for input parameter v. */);
</code></pre>


<p>Note that these blocks have the same structure and meaning as the special comment blocks in the previous section only the &lt; indicates that the member is located in front of the block instead of after the block.</p>

<p>Here is an example of the use of these comment blocks:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! A test class */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Afterdoc_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** An enum type. </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     *  The documentation block cannot be put after the enum! </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> EnumType</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> EVal1,     </span><span class="doxyHighlightComment">/**&lt; enum value 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> EVal2      </span><span class="doxyHighlightComment">/**&lt; enum value 2 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> member();   </span><span class="doxyHighlightComment">//!&lt; a member function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">protected</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value;       </span><span class="doxyHighlightComment">/*!&lt; an integer value */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

 
 Click <a href="pathname:///examples/afterdoc/html/class_afterdoc___test.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

:::warning
<p>These blocks can only be used to document <em>members</em> and <em>parameters</em>. They cannot be used to document files, classes, unions, structs, groups, namespaces, macros, and enums themselves. Furthermore, the structural commands mentioned in the next section (like <span class="doxyComputerOutput">\class</span>) are not allowed inside these comment blocks.</p>
:::


:::warning
<p>Be careful using this construct as part of a macro definition, because when <a href="/web-doxygen/docs/pages/config/#cfg_macro_expansion">MACRO_EXPANSION</a> is set to <span class="doxyComputerOutput">YES</span> at the places where the macro is applied, also the comment will be substituted and this comment is then used as documentation for the last item encountered and not for the macro definition itself!</p>
:::


#### Examples {#docexamples}


<p>Here is an example of a documented piece of C++ code using the Qt style:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//!  A test class. </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  A more elaborate class description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">QTstyle_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! An enum.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*! More detailed enum description. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> TEnum { </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                 TVal1, </span><span class="doxyHighlightComment">/*!&lt; Enum value TVal1. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                 TVal2, </span><span class="doxyHighlightComment">/*!&lt; Enum value TVal2. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                 TVal3  </span><span class="doxyHighlightComment">/*!&lt; Enum value TVal3. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">               } </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">         //! Enum pointer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">         /*! Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">         *enumPtr, </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">         //! Enum variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">         /*! Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">         enumVar;  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A constructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      A more elaborate description of the constructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    QTstyle_Test();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A destructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      A more elaborate description of the destructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   ~QTstyle_Test();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A normal member taking two arguments and returning an integer value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \param a an integer argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \param s a constant character pointer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \return The test results</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \sa QTstyle_Test(), ~QTstyle_Test(), testMeToo() and publicVar()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> testMe(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A pure virtual member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \sa testMe()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \param c1 the first argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      \param c2 the second argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> testMeToo(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c1,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c2) = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A public variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> publicVar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    //! A function variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    int (*handler)(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> b);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>

 
 Click <a href="pathname:///examples/qtstyle/html/class_q_tstyle___test.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

<p>The brief descriptions are included in the member overview of a class, namespace or file and are printed using a small italic font (this description can be hidden by setting <a href="/web-doxygen/docs/pages/config/#cfg_brief_member_desc">BRIEF_MEMBER_DESC</a> to <span class="doxyComputerOutput">NO</span> in the configuration file). By default the brief descriptions become the first sentence of the detailed descriptions (but this can be changed by setting the <a href="/web-doxygen/docs/pages/config/#cfg_repeat_brief">REPEAT_BRIEF</a> tag to <span class="doxyComputerOutput">NO</span>). Both the brief and the detailed descriptions are optional for the Qt style.</p>

<p>By default a Javadoc style documentation block behaves the same way as a Qt style documentation block. This is not according the Javadoc specification however, where the first sentence of the documentation block is automatically treated as a brief description. To enable this behavior you should set <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> to YES in the configuration file. If you enable this option and want to put a dot in the middle of a sentence without ending it, you should put a backslash and a space after it. Here is an example:</p>


<pre><code>/** Brief description (e.g.\ using only a few words). Details follow. */
</code></pre>


<p>Here is the same piece of code as shown above, this time documented using the Javadoc style and <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> set to YES:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  A test class. A more elaborate class description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Javadoc_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     * An enum.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     * More detailed enum description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> TEnum { </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          TVal1, </span><span class="doxyHighlightComment">/**&lt; enum value TVal1. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          TVal2, </span><span class="doxyHighlightComment">/**&lt; enum value TVal2. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          TVal3  </span><span class="doxyHighlightComment">/**&lt; enum value TVal3. */</span><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">         } </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       *enumPtr, </span><span class="doxyHighlightComment">/**&lt; enum pointer. Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       enumVar;  </span><span class="doxyHighlightComment">/**&lt; enum variable. Details. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * A constructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * A more elaborate description of the constructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      Javadoc_Test();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * A destructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * A more elaborate description of the destructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     ~Javadoc_Test();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * a normal member taking two arguments and returning an integer value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @param a an integer argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @param s a constant character pointer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @see Javadoc_Test()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @see ~Javadoc_Test()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @see testMeToo()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @see publicVar()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @return The test results</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> testMe(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * A pure virtual member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @see testMe()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @param c1 the first argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * @param c2 the second argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> testMeToo(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c1,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c2) = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /** </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * a public variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> publicVar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">      /**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * a function variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">       int (*handler)(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> b);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>

 
 Click <a href="pathname:///examples/jdstyle/html/class_javadoc___test.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

<p>Similarly, if one wishes the first sentence of a Qt style documentation block to automatically be treated as a brief description, one may set <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT_AUTOBRIEF</a> to YES in the configuration file.</p>

#### Documentation at other places {#structuralcommands}


<p>In the examples in the previous section the comment blocks were always located <em>in front</em> of the declaration or definition of a file, class or namespace or <em>in front</em> or <em>after</em> one of its members. Although this is often comfortable, there may sometimes be reasons to put the documentation somewhere else. For documenting a file this is even required since there is no such thing as "in front of a file".</p>

<p>Doxygen allows you to put your documentation blocks practically anywhere (the exception is inside the body of a function or inside a normal C style comment block).</p>

<p>The price you pay for not putting the documentation block directly before (or after) an item is the need to put a structural command inside the documentation block, which leads to some duplication of information. So in practice you should <em>avoid</em> the use of structural commands <em>unless</em> other requirements force you to do so.</p>

<p>Structural commands (like <a href="/web-doxygen/docs/pages/commands/#cmd_intro">all other commands</a>) start with a backslash (<span class="doxyComputerOutput">\</span>), or an at-sign (<span class="doxyComputerOutput">@</span>) if you prefer Javadoc style, followed by a command name and one or more parameters. For instance, if you want to document the class <span class="doxyComputerOutput">Test</span> in the example above, you could have also put the following documentation block somewhere in the input that is read by Doxygen:</p>


<pre><code>/*! \class Test
    \brief A test class.

    A more detailed class description.
*/
</code></pre>


<p>Here the special command <span class="doxyComputerOutput">\class</span> is used to indicate that the comment block contains documentation for the class <span class="doxyComputerOutput">Test</span>. Other structural commands are:</p>

<ul class="doxyList ">
<li><span class="doxyComputerOutput">\struct</span> to document a C-struct.</li>
<li><span class="doxyComputerOutput">\union</span> to document a union.</li>
<li><span class="doxyComputerOutput">\enum</span> to document an enumeration type.</li>
<li><span class="doxyComputerOutput">\fn</span> to document a function.</li>
<li><span class="doxyComputerOutput">\var</span> to document a variable or typedef or enum value.</li>
<li><span class="doxyComputerOutput">\def</span> to document a #define.</li>
<li><span class="doxyComputerOutput">\typedef</span> to document a type definition.</li>
<li><span class="doxyComputerOutput">\file</span> to document a file.</li>
<li><span class="doxyComputerOutput">\namespace</span> to document a namespace.</li>
<li><span class="doxyComputerOutput">\package</span> to document a Java package.</li>
<li><span class="doxyComputerOutput">\interface</span> to document an IDL interface.</li>
</ul>

<p>See section <a href="/web-doxygen/docs/pages/commands">Special Commands</a> for detailed information about these and many other commands.</p>

<p>To document a member of a C++ class, you must also document the class itself. The same holds for namespaces. To document a global C function, typedef, enum or preprocessor definition you must first document the file that contains it (usually this will be a header file, because that file contains the information that is exported to other source files).</p>

:::danger
<p>Let's repeat that, because it is often overlooked: to document global objects (functions, typedefs, enum, macros, etc), you <em>must</em> document the file in which they are defined. In other words, there <em>must</em> at least be a</p>


<pre><code>/*! \file */
</code></pre>


<p>or a</p>


<pre><code>/** @file */
</code></pre>


<p>line in this file.</p>
:::


<p>Here is an example of a C header named <span class="doxyComputerOutput">structcmd.h</span> that is documented using structural commands:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \file structcmd.h</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief A Documented file.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \def MAX(a,b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief A macro that returns the maximum of \a a and \a b.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \var typedef unsigned int UINT32</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief A type definition for a .</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \var int errno</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief Contains the last error code.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \warning Not thread safe!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn int open(const char *pathname,int flags)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief Opens a file descriptor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param pathname The name of the descriptor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param flags Opening flags.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn int close(int fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief Closes the file descriptor \a fd.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param fd The descriptor to close.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn size_t write(int fd,const char *buf, size_t count)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief Writes \a count bytes from \a buf to the filedescriptor \a fd.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param fd The descriptor to write to.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param buf The data buffer to write.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param count The number of bytes to write.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn int read(int fd,char *buf,size_t count)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief Read bytes from a file descriptor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param fd The descriptor to read from.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param buf The buffer to read into.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \param count The number of bytes to read.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MAX(a,b) (((a)&gt;(b))?(a):(b))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> UINT32;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> errno;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> open(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> close(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> write(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> read(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">);</span></span></div>

</div>

 
 Click <a href="pathname:///examples/structcmd/html/structcmd_8h.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

<p>Because each comment block in the example above contains a structural command, all the comment blocks could be moved to another location or input file (the source file for instance), without affecting the generated documentation. The disadvantage of this approach is that prototypes are duplicated, so all changes have to be made twice! Because of this you should first consider if this is really needed, and avoid structural commands if possible. I often receive examples that contain \fn command in comment blocks which are place in front of a function. This is clearly a case where the \fn command is redundant and will only lead to problems.</p>

<p>When you place a comment block in a file with one of the following extensions <span class="doxyComputerOutput">.dox</span>, <span class="doxyComputerOutput">.txt</span>, <span class="doxyComputerOutput">.doc</span>, <span class="doxyComputerOutput">.md</span> or <span class="doxyComputerOutput">.markdown</span> or when the extension maps to <span class="doxyComputerOutput">md</span> by means of the <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">EXTENSION_MAPPING</a> then Doxygen will hide this file from the file list.</p>

<p>If you have a file that Doxygen cannot parse but still would like to document it, you can show it as-is using <a href="/web-doxygen/docs/pages/commands/#cmdverbinclude">\verbinclude</a>, e.g.</p>


<pre><code>/*! \file myscript.sh
 *  Look at this nice script:
 *  \verbinclude myscript.sh
 */
</code></pre>


<p>Make sure that the script is explicitly listed in the <a href="/web-doxygen/docs/pages/config/#cfg_input">INPUT</a> or that <a href="/web-doxygen/docs/pages/config/#cfg_file_patterns">FILE_PATTERNS</a> includes the <span class="doxyComputerOutput">.sh</span> extension and the script can be found in the path set via <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a>.</p>

### Comment blocks in Python {#pythonblocks}


<p>For Python there is a standard way of documenting the code using so called documentation strings (<span class="doxyComputerOutput">"""</span>). Such strings are stored in <span class="doxyComputerOutput">__doc__</span> and can be retrieved at runtime. Doxygen will extract such comments and assume they have to be represented in a preformatted way.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"""@package docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">Documentation for this module.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"""</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">func():</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"""Documentation for a function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    """</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">pass</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">PyClass:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"""Documentation for a class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    """</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">__init__(self):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"""The constructor."""</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        self._memVar = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">PyMethod(self):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"""Documentation for a method."""</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">pass</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span></span></div>

</div>

 
 Click <a href="pathname:///examples/docstring/html/namespacedocstring.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

:::info
<p>When using <span class="doxyComputerOutput">"""</span> none of Doxygen's <a href="/web-doxygen/docs/pages/commands/#cmd_intro">special commands</a> are supported and the text is shown as verbatim text see <a href="/web-doxygen/docs/pages/commands/#cmdverbatim">\verbatim</a>. To have the Doxygen's <a href="/web-doxygen/docs/pages/commands/#cmd_intro">special commands</a> and have the text as regular documentation instead of <span class="doxyComputerOutput">"""</span> use <span class="doxyComputerOutput">"""!</span> or set <a href="/web-doxygen/docs/pages/config/#cfg_python_docstring">PYTHON_DOCSTRING</a> to <span class="doxyComputerOutput">NO</span> in the configuration file.</p>
:::


:::info
<p>Instead of <span class="doxyComputerOutput">"""</span> one can also use <span class="doxyComputerOutput">'''</span>.</p>
:::


<p>There is also another way to document Python code using comments that start with "##" or "##&lt;". These type of comment blocks are more in line with the way documentation blocks work for the other languages supported by Doxygen and this also allows the use of special commands.</p>

<p>Here is the same example again but now using Doxygen style comments:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">## @package pyexample</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#  Documentation for this module.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#  More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">## Documentation for a function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#  More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">func():</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">pass</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">## Documentation for a class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">#  More details.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">PyClass:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">## The constructor.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">__init__(self):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        self._memVar = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">## Documentation for a method.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    #  @param self The object pointer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">PyMethod(self):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">pass</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">## A class variable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    classVar = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">## @var _memVar</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    #  a member variable</span></span></div>

</div>

 
 Click <a href="pathname:///examples/pyexample/html/namespacepyexample.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

<p>Since python looks more like Java than like C or C++, you should set <a href="/web-doxygen/docs/pages/config/#cfg_optimize_output_java">OPTIMIZE_OUTPUT_JAVA</a> to <span class="doxyComputerOutput">YES</span> in the configuration file.</p>

### Comment blocks in VHDL {#vhdlblocks}


<p>For VHDL a comment normally start with "--". Doxygen will extract comments starting with "--!". There are only two types of comment blocks in VHDL; a one line "--!" comment representing a brief description, and a multi-line "--!" comment (where the "--!" prefix is repeated for each line) representing a detailed description.</p>

<p>Comments are always located in front of the item that is being documented with one exception: for ports the comment can also be after the item and is then treated as a brief description for the port.</p>

<p>Here is an example VHDL file with Doxygen comments:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">-------------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! @file</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! @brief 2:1 Mux using with-select</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">-------------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! Use standard library</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightVhdlKeyword">library </span><span class="doxyHighlightKeywordFlow">ieee</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! Use logic elements</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightVhdlKeyword">    use </span><span class="doxyHighlight">ieee.std_logic_1164.</span><span class="doxyHighlightKeywordFlow">all</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! Mux entity brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! Detailed description of this </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! mux design element.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">entity </span><span class="doxyHighlight">mux_using_with </span><span class="doxyHighlightKeywordFlow">is</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">port</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightVhdlChar">din_0</span><span class="doxyHighlight">   </span><span class="doxyHighlightVhdlChar">:</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">std_logic</span><span class="doxyHighlight">;</span><span class="doxyHighlightComment"> --! Mux first input</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightVhdlChar">din_1</span><span class="doxyHighlight">   </span><span class="doxyHighlightVhdlChar">:</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">std_logic</span><span class="doxyHighlight">;</span><span class="doxyHighlightComment"> --! Mux Second input</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightVhdlChar">sel</span><span class="doxyHighlight">     </span><span class="doxyHighlightVhdlChar">:</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">std_logic</span><span class="doxyHighlight">;</span><span class="doxyHighlightComment"> --! Select input</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightVhdlChar">mux_out</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">:</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">out</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">std_logic</span><span class="doxyHighlightComment">  --! Mux output</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightVhdlChar">)</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">end</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">entity</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! @brief Architecture definition of the MUX</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">--! @details More details about this mux element.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">architecture</span><span class="doxyHighlight"> behavior </span><span class="doxyHighlightKeywordFlow">of</span><span class="doxyHighlight"> mux_using_with </span><span class="doxyHighlightKeywordFlow">is</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightVhdlKeyword">begin</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">with</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">(</span><span class="doxyHighlightVhdlChar">sel</span><span class="doxyHighlightVhdlChar">)</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">select</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightVhdlChar">mux_out</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">&lt;=</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">din_0</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">when</span><span class="doxyHighlight"> </span><span class="doxyHighlightVhdlChar">'</span><span class="doxyHighlightVhdlLogic">0</span><span class="doxyHighlightVhdlChar">'</span><span class="doxyHighlightVhdlChar">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightVhdlChar">din_1</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">when</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">others</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">end</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">architecture</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>

 
 Click <a href="pathname:///examples/mux/html/mux_8vhdl.html">here</a>
 for the corresponding HTML documentation that is generated by Doxygen.
 

<p>As of VHDL 2008 it is also possible to use <span class="doxyComputerOutput">/</span><span class="doxyComputerOutput">*</span> style comments.
<br/>
 Doxygen will handle <span class="doxyComputerOutput">/</span><span class="doxyComputerOutput">* ... *</span><span class="doxyComputerOutput">/</span>as plain comments and <span class="doxyComputerOutput">/</span><span class="doxyComputerOutput">*! ... *</span><span class="doxyComputerOutput">/</span> style comments as special comments to be parsed by Doxygen.</p>

<p>To get proper looking output you need to set <a href="/web-doxygen/docs/pages/config/#cfg_optimize_output_vhdl">OPTIMIZE_OUTPUT_VHDL</a> to <span class="doxyComputerOutput">YES</span> in the configuration file. This will also affect a number of other settings. When they were not already set correctly Doxygen will produce a warning telling which settings where overruled.</p>

### Comment blocks in Fortran {#fortranblocks}


<p>When using Doxygen for Fortran code you should set <a href="/web-doxygen/docs/pages/config/#cfg_optimize_for_fortran">OPTIMIZE_FOR_FORTRAN</a> to <span class="doxyComputerOutput">YES</span>.</p>

<p>The parser tries to guess if the source code is fixed format Fortran or free format Fortran code. This may not always be correct. If not one should use <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">EXTENSION_MAPPING</a> to correct this. By setting <span class="doxyComputerOutput">EXTENSION_MAPPING = f=FortranFixed f90=FortranFree</span> files with extension <span class="doxyComputerOutput">f</span> are interpreted as fixed format Fortran code and files with extension <span class="doxyComputerOutput">f90</span> are interpreted as free format Fortran code.</p>

<p>For Fortran "!&gt;" or "!&lt;" starts a comment and "!!" or "!&gt;" can be used to continue an one line comment into a multi-line comment.</p>

<p>Here is an example of a documented Fortran subroutine:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">!&gt; Build the restriction matrix for the aggregation</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">!! method.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">!! @param aggr information about the aggregates</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">!! @todo Handle special case</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">subroutine </span><span class="doxyHighlight">intrestbuild(A,aggr,Restrict,A_ghost)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">implicit none</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">Type</span><span class="doxyHighlight">(SpMtx), </span><span class="doxyHighlightKeywordType">intent(in)</span><span class="doxyHighlight"> :: A</span><span class="doxyHighlightComment"> !&lt; our fine level matrix</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">Type</span><span class="doxyHighlight">(Aggrs), </span><span class="doxyHighlightKeywordType">intent(in)</span><span class="doxyHighlight"> :: aggr</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">Type</span><span class="doxyHighlight">(SpMtx), </span><span class="doxyHighlightKeywordType">intent(out)</span><span class="doxyHighlight"> :: Restrict</span><span class="doxyHighlightComment"> !&lt; Our restriction matrix</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">!...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">end subroutine</span></span></div>

</div>


<p>As an alternative you can also use comments in fixed format code:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">C&gt; Function comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">C&gt; another line of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">function </span><span class="doxyHighlight">a(i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">C&gt; input parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">integer</span><span class="doxyHighlight"> i</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">end function </span><span class="doxyHighlight">A</span></span></div>

</div>


## Anatomy of a comment block {#docstructure}


<p>The previous section focused on how to make the comments in your code known to Doxygen, it explained the difference between a brief and a detailed description, and the use of structural commands.</p>

<p>In this section we look at the contents of the comment block itself.</p>

<p>Doxygen supports various styles of formatting your comments.</p>

<p>The simplest form is to use plain text. This will appear as-is in the output and is ideal for a short description.</p>

<p>For longer descriptions you often will find the need for some more structure, like a block of verbatim text, a list, or a simple table. For this Doxygen supports the <a href="https://daringfireball.net/projects/markdown/syntax">Markdown</a> syntax, including parts of the <a href="https://michelf.ca/projects/php-markdown/extra/">Markdown Extra</a> extension.</p>

<p>Markdown is designed to be very easy to read and write. Its formatting is inspired by plain text mail. Markdown works great for simple, generic formatting, like an introduction page for your project. Doxygen also supports reading of markdown files directly. For more details see chapter <a href="/web-doxygen/docs/pages/markdown">Markdown support</a>.</p>

<p>For programming language specific formatting Doxygen has two forms of additional markup on top of Markdown formatting.</p>

<ol class="doxyList" type="1">
<li><a href="https://en.wikipedia.org/wiki/Javadoc">Javadoc</a> like markup. See <a href="/web-doxygen/docs/pages/commands">Special Commands</a> for a complete overview of all commands supported by Doxygen.</li>
<li><a href="https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/xmldoc/recommended-tags-for-documentation-comments">XML</a> markup as specified in the <a href="http://standards.iso.org/ittf/PubliclyAvailableStandards/c042926_ISO_IEC_23270_2006(E).zip">C# standard</a>. See <a href="/web-doxygen/docs/pages/xmlcmds">XML Commands</a> for the XML commands supported by Doxygen.</li>
</ol>

<p>If this is still not enough Doxygen also supports a <a href="/web-doxygen/docs/pages/htmlcmds">subset</a> of the <a href="https://en.wikipedia.org/wiki/HTML">HTML</a> markup language.</p>
 
Go to the <a href="/docs/pages/markdown/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
