---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/diagrams
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Graphs and diagrams




<p>Doxygen has built-in support to generate inheritance diagrams for C++ classes.</p>


<p>Doxygen can use the "dot" tool from graphviz to generate more advanced diagrams and graphs. Graphviz is an open-source, cross-platform graph drawing toolkit and can be found at <a href="https://www.graphviz.org/">https://www.graphviz.org/</a></p>


<p>If you have the "dot" tool in the path, you can set <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> to <span class="doxyComputerOutput">YES</span> in the configuration file to let Doxygen use it.</p>


<p>Doxygen uses the "dot" tool to generate the following graphs:</p>


<ul class="doxyList ">
<li>A graphical representation of the class hierarchy will be drawn, along with the textual one. Currently this feature is supported for HTML only.
<br/>
 <b>Warning:</b> When you have a very large class hierarchy where many classes derive from a common base class, the resulting image may become too big to handle for some browsers.</li>
<li>An inheritance graph will be generated for each documented class showing the direct and indirect inheritance relations. This disables the generation of the built-in class inheritance diagrams.</li>
<li>An include dependency graph is generated for each documented file that includes at least one other file. This feature is currently supported for HTML and RTF only.</li>
<li>An inverse include dependency graph is also generated showing for a (header) file, which other files include it.</li>
<li>A graph is drawn for each documented class and struct that shows:

<ul class="doxyList ">
<li>the inheritance relations with base classes.</li>
<li>the usage relations with other structs and classes (e.g. class <span class="doxyComputerOutput">A</span> has a member variable <span class="doxyComputerOutput">m_a</span> of type class <span class="doxyComputerOutput">B</span>, then <span class="doxyComputerOutput">A</span> has an arrow to <span class="doxyComputerOutput">B</span> with <span class="doxyComputerOutput">m_a</span> as label).</li>
</ul></li>
<li>if <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a> is set to YES, a graphical call graph is drawn for each function showing the functions that the function directly or indirectly calls (see also section <a href="/web-doxygen/docs/pages/commands/#cmdcallgraph">\callgraph</a> and section <a href="/web-doxygen/docs/pages/commands/#cmdhidecallgraph">\hidecallgraph</a>).</li>
<li>if <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a> is set to YES, a graphical caller graph is drawn for each function showing the functions that the function is directly or indirectly called by (see also section <a href="/web-doxygen/docs/pages/commands/#cmdcallergraph">\callergraph</a> and section <a href="/web-doxygen/docs/pages/commands/#cmdhidecallergraph">\hidecallergraph</a>).</li>
<li>If <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a> is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate graphs that show the directory dependencies for every directory. The graph will show directories as boxes. Subdirectories are shown nested into the box of its parent directory. The depth of the graph is configured through <a href="/web-doxygen/docs/pages/config/#cfg_dir_graph_max_depth">DIR_GRAPH_MAX_DEPTH</a>. Include dependencies between the directories are shown as arrows.</li>
</ul>

<p>Using a <a href="/web-doxygen/docs/pages/customize">layout file</a> you can determine which of the graphs are actually shown.</p>


<p>The options <a href="/web-doxygen/docs/pages/config/#cfg_dot_graph_max_nodes">DOT_GRAPH_MAX_NODES</a> and <a href="/web-doxygen/docs/pages/config/#cfg_max_dot_graph_depth">MAX_DOT_GRAPH_DEPTH</a> can be used to limit the size of the various graphs.</p>


<p>The elements in the class diagrams in HTML and RTF have the following meaning:</p>


<ul class="doxyList ">
<li>A <b>yellow</b> box indicates a class. A box can have a little marker in the lower right corner to indicate that the class contains base classes that are hidden. For the class diagrams the maximum tree width is currently 8 elements. If a tree is wider some nodes will be hidden. If the box is filled with a dashed pattern the inheritance relation is virtual.</li>
<li>A <b>white</b> box indicates that the documentation of the class is currently shown.</li>
<li>A <b>gray</b> box indicates an undocumented class.</li>
<li>A <b>solid dark blue</b> arrow indicates public inheritance.</li>
<li>A <b>dashed dark green</b> arrow indicates protected inheritance.</li>
<li>A <b>dotted dark green</b> arrow indicates private inheritance.</li>
</ul>

<p>The elements in the class diagram in <code>{\LaTeX}</code> have the following meaning:</p>


<ul class="doxyList ">
<li>A <b>white</b> box indicates a class. A <b>marker</b> in the lower right corner of the box indicates that the class has base classes that are hidden. If the box has a <b>dashed</b> border this indicates virtual inheritance.</li>
<li>A <b>solid</b> arrow indicates public inheritance.</li>
<li>A <b>dashed</b> arrow indicates protected inheritance.</li>
<li>A <b>dotted</b> arrow indicates private inheritance.</li>
</ul>

<p>The elements in the graphs generated by the dot tool have the following meaning:</p>


<ul class="doxyList ">
<li>A <b>white</b> box indicates a class or struct or file.</li>
<li>A box with a <b>red</b> border indicates a node that has <em>more</em> arrows than are shown! In other words: the graph is <em>truncated</em> with respect to this node. The reason why a graph is sometimes truncated is to prevent images from becoming too large. For the graphs generated with dot Doxygen tries to limit the width of the resulting image to 1024 pixels. 
<br/></li>
<li>A <b>black</b> box indicates that the class' documentation is currently shown.</li>
<li>A <b>dark blue</b> arrow indicates an include relation (for the include dependency graph) or public inheritance (for the other graphs).</li>
<li>A <b>dark green</b> arrow indicates protected inheritance.</li>
<li>A <b>dark red</b> arrow indicates private inheritance.</li>
<li>A <b>purple dashed</b> arrow indicated a "usage" relation, the edge of the arrow is labeled with the variable(s) responsible for the relation. Class <span class="doxyComputerOutput">A</span> uses class <span class="doxyComputerOutput">B</span>, if class <span class="doxyComputerOutput">A</span> has a member variable <span class="doxyComputerOutput">m</span> of type C, where B is a subtype of C (e.g. <span class="doxyComputerOutput">C</span> could be <span class="doxyComputerOutput">B</span>, <span class="doxyComputerOutput">B*</span>, <span class="doxyComputerOutput">T&lt;B&gt;*</span>).</li>
</ul>

<p>The elements in the directory dependency graphs have the following meaning:</p>


<ul class="doxyList ">
<li>A box with a <b>bold</b> border indicates the directory that the directory dependency graph has been generated for.</li>
<li>A box with a <b>red solid</b> border indicates a directory whose subdirectories are not shown in the graph ("truncated"). To configure the depth of subdirectories that are shown in the graph see <a href="/web-doxygen/docs/pages/config/#cfg_dir_graph_max_depth">DIR_GRAPH_MAX_DEPTH</a>.</li>
<li>A box with a <b>red dashed</b> border indicates a truncated directory whose parent directories are not shown in the graph either.</li>
<li>A box with a <b>dashed</b> border other than red indicates that not all but at least one subdirectory are shown.</li>
<li>A box with a <b>light gray</b> border indicates a directory with both of the following two attributes:

<ul class="doxyList ">
<li>Its parent directory is not shown.</li>
<li>At least one subdirectory is shown.</li>
</ul></li>
<li>A box with <b>no background color</b> indicates a directory which is not a subdirectory of the origin's parent directories which are shown. The origin is the directory for which the directory dependency graph is shown.</li>
<li>An <b>arrow</b> between two boxes indicates an include dependency between two directories. The include dependency exists if a file in a directory includes a file of another directory. If a directory that is involved in an include dependency is not shown in the graph, the arrow is attached to the first parent directory that is shown. This parent directory is shown as truncated (see above).</li>
</ul>

<p>Here are a couple of header files that together show the various diagrams that Doxygen can generate:</p>


<p><span class="doxyComputerOutput">diagrams_a.h</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifndef DIAGRAMS_A_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DIAGRAMS_A_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">A { </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">: A *m_self; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>

</div>


<p><span class="doxyComputerOutput">diagrams_b.h</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifndef DIAGRAMS_B_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DIAGRAMS_B_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">A;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">B { </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">: A *m_a; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>

</div>


<p><span class="doxyComputerOutput">diagrams_c.h</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifndef DIAGRAMS_C_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DIAGRAMS_C_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#include "diagrams_c.h"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">D;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C : </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight"> A { </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">: D *m_d; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>

</div>


<p><span class="doxyComputerOutput">diagrams_d.h</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifndef DIAGRAM_D_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DIAGRAM_D_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#include "diagrams_a.h"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#include "diagrams_b.h"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">D : </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">protected</span><span class="doxyHighlight">  A, </span><span class="doxyHighlightKeyword">private</span><span class="doxyHighlight"> B { </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">: C m_c; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>

</div>


<p><span class="doxyComputerOutput">diagrams_e.h</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifndef DIAGRAM_E_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DIAGRAM_E_H</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#include "diagrams_d.h"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">E : </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight"> D {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>

</div>

 
Click <a href="pathname:///examples/diagrams/html/annotated.html">here</a>
for the corresponding HTML documentation that is generated by Doxygen.


<p>Note <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> <span class="doxyComputerOutput">=</span> <span class="doxyComputerOutput">YES</span> is used to generate the diagrams.</p>

 
Go to the <a href="/docs/pages/preprocessing/">next</a> section or return to the
<a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
