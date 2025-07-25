---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /pages/customize
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Customizing the output




<p>Doxygen provides various levels of customization. The section <a href="#minor_tweaks">Minor Tweaks</a> discusses what to do if you want to do minor tweaking to the look and feel of the output. The section <a href="#layout">Layout</a> show how to reorder and hide certain information on a page. The section <a href="#xmlgenerator">XML output</a> show how to generate whatever output you want based on the XML output produced by Doxygen.</p>


## Minor Tweaks {#minor_tweaks}


<p>The next subsections describe some aspects that can be tweaked with little effort.</p>


### Overall Color {#minor_tweaks_colors}


<p>To change the overall color of the HTML output Doxygen provides three options</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_hue">HTML_COLORSTYLE_HUE</a></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_sat">HTML_COLORSTYLE_SAT</a></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_gamma">HTML_COLORSTYLE_GAMMA</a></li>
</ul>

<p>to change the hue, saturation, and gamma correction of the colors respectively.</p>


<p>For your convenience the GUI frontend <a href="/web-doxygen/docs/pages/doxywizard-usage">Doxywizard</a> has a control that allows you to see the effect of changing the values of these options on the output in real time.</p>


### Navigation {#minor_tweaks_treeview}


<p>By default, Doxygen will show a title area spanning the full width of the page and below the contents with a navigation tree as a sidebar on the left hand side of each HTML page.</p>


<p>This corresponds to the following settings in the Doxyfile:</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <span class="doxyComputerOutput">NO</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_treeview.png"></img>
</figure></p>


<p>you can make the side bar span the whole height of the page using</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <span class="doxyComputerOutput">YES</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_sidebar.png"></img>
</figure></p>


<p>you can also replace the navigation tree by tabs on top of every HTML page, corresponding to the following settings:</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">NO</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">NO</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_notreeview.png"></img>
</figure></p>


<p>or even have both forms of navigation:</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">NO</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <span class="doxyComputerOutput">NO</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_treeview.png"></img>
</figure></p>


<p>and this also works with the side bar spanning the full height</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">NO</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <span class="doxyComputerOutput">YES</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_sidebar.png"></img>
</figure></p>


<p>if you already use an external index (i.e. have one of the following options enabled <a href="/web-doxygen/docs/pages/config/#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a>, <a href="/web-doxygen/docs/pages/config/#cfg_generate_eclipsehelp">GENERATE_ECLIPSEHELP</a>, <a href="/web-doxygen/docs/pages/config/#cfg_generate_qhp">GENERATE_QHP</a>, or <a href="/web-doxygen/docs/pages/config/#cfg_generate_docset">GENERATE_DOCSET</a>) then you can also disable all indices, like so:</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <span class="doxyComputerOutput">YES</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <span class="doxyComputerOutput">NO</span></li>
</ul>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_notreeview.png"></img>
</figure></p>


### Dynamic Content {#minor_tweaks_dynsection}


<p>To make the HTML output more interactive, Doxygen provides a number of options that are disabled by default:</p>


<ul class="doxyList ">
<li>enabling <a href="/web-doxygen/docs/pages/config/#cfg_html_dynamic_sections">HTML_DYNAMIC_SECTIONS</a> will make Doxygen hide certain content (like graphs) in the HTML by default, and let the reader expand these sections on request.</li>
<li>enabling <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> along with <a href="/web-doxygen/docs/pages/config/#cfg_interactive_svg">INTERACTIVE_SVG</a> while setting <a href="/web-doxygen/docs/pages/config/#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> to <span class="doxyComputerOutput">svg</span>, will make Doxygen produce SVG images that will allow the user to zoom and pan (this only happens when the size of the images exceeds a certain size).</li>
</ul>

### Header, Footer, and Stylesheet changes {#minor_tweaks_header_css}


<p>To tweak things like fonts or colors, margins, or other look &amp; feel aspects of the HTML output in detail, you can create a different <a href="https://www.w3schools.com/css/default.asp">cascading style sheet</a>. You can also let Doxygen use a custom header and footer for each HTML page it generates, for instance to make the output conform to the style used on the rest of your web site.</p>


<p>To do this first run Doxygen as follows:</p>



<pre><code>doxygen -w html header.html footer.html customdoxygen.css
</code></pre>


<p>This will create 3 files:</p>


<ul class="doxyList ">
<li>header.html is a HTML fragment which Doxygen normally uses to start a HTML page. Note that the fragment ends with a body tag and that is contains a couple of commands of the form $word. These will be replaced by Doxygen on the fly.</li>
<li>footer.html is a HTML fragment which Doxygen normally uses to end a HTML page. Also here special commands can be used. This file contain the link to www.doxygen.org and the body and html end tags.</li>
<li>customdoxygen.css is the default cascading style sheet used by Doxygen. It is recommended only to look into this file and overrule some settings you like by putting them in a separate stylesheets and referencing those extra files via <a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a>.</li>
</ul>

<p>You should edit these files and then reference them from the configuration file.</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML_HEADER</a> = <span class="doxyComputerOutput">header.html</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_footer">HTML_FOOTER</a> = <span class="doxyComputerOutput">footer.html</span></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> = <span class="doxyComputerOutput">my_customdoxygen.css</span></li>
</ul>


:::info
<p>it is not longer recommended to use <a href="/web-doxygen/docs/pages/config/#cfg_html_stylesheet">HTML_STYLESHEET</a>, as it make it difficult to upgrade to a newer version of Doxygen. Use <a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> instead.</p>
:::


<p>See the documentation of the <a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML_HEADER</a> tag for more information about the possible meta commands you can use inside your custom header.</p>



:::info
<p>You should not put the style sheet in the HTML output directory. Treat it as a source file. Doxygen will copy it for you.</p>
:::



:::info
<p>If you use images or other external content in a custom header you need to make sure these end up in the HTML output directory yourself, for instance by writing a script that runs Doxygen can then copies the images to the output.</p>
:::



:::warning
<p>The structure of headers and footers may change after upgrading to a newer version of Doxygen, so if you are using a custom header or footer, it might not produce valid output anymore after upgrading.</p>
:::


## Changing the layout of pages {#layout}


<p>In some cases you may want to change the way the output is structured. A different style sheet or custom headers and footers do not help in such case.</p>


<p>The solution Doxygen provides is a layout file, which you can modify and Doxygen will use to control what information is presented, in which order, and to some extent also how information is presented. The layout file is an XML file.</p>


<p>The default layout can be generated by Doxygen using the following command:</p>



<pre><code>doxygen -l
</code></pre>


<p>optionally the name of the layout file can be specified, if omitted <span class="doxyComputerOutput">DoxygenLayout.xml</span> will be used.</p>


<p>The next step is to mention the layout file in the configuration file (see also <a href="/web-doxygen/docs/pages/config/#cfg_layout_file">LAYOUT_FILE</a>)</p>



<pre><code>LAYOUT_FILE = DoxygenLayout.xml
</code></pre>


<p>To change the layout all you need to do is edit the layout file.</p>


<p>The toplevel structure of the file looks as follows:</p>



<pre><code>&lt;doxygenlayout version="1.0"&gt;
  &lt;navindex&gt;
    ...
  &lt;/navindex&gt;
  &lt;class&gt;
    ...
  &lt;/class&gt;
  &lt;namespace&gt;
    ...
  &lt;/namespace&gt;
  &lt;concept&gt;
    ...
  &lt;/concept&gt;
  &lt;file&gt;
    ...
  &lt;/file&gt;
  &lt;group&gt;
    ...
  &lt;/group&gt;
  &lt;directory&gt;
    ...
  &lt;/directory&gt;
&lt;/doxygenlayout&gt;
</code></pre>


<p>The root element of the XML file is <span class="doxyComputerOutput">doxygenlayout</span>, it has an attribute named <span class="doxyComputerOutput">version</span>, which will be used in the future to cope with changes that are not backward compatible.</p>


<p>The first section, identified by the <span class="doxyComputerOutput">navindex</span> element, represents the layout of the navigation tabs displayed at the top of each HTML page. At the same time it also controls the items in the navigation tree in case <a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> is enabled. Each tab is represented by a <span class="doxyComputerOutput">tab</span> element in the XML file.</p>


<p>You can hide tabs by setting the <span class="doxyComputerOutput">visible</span> attribute to <span class="doxyComputerOutput">no</span>. You can also override the default title of a tab by specifying it as the value of the <span class="doxyComputerOutput">title</span> attribute. If the title field is the empty string (the default) then Doxygen will fill in an appropriate language specific title.</p>


<p>You can reorder the tabs by moving the tab elements in the XML file within the <span class="doxyComputerOutput">navindex</span> element and even change the tree structure. Do not change the value of the <span class="doxyComputerOutput">type</span> attribute however. Only a fixed set of types are supported, each representing a link to a specific index.</p>


<p>You can also add custom tabs using a type with name "user". Here is an example that shows how to add a tab with title "Google" pointing to www.google.com:</p>



<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="user" url="http://www.google.com" title="Google"/&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


<p>The url field can also be a relative URL. If the URL starts with @ref the link will point to a documented entities, such as a class, a function, a group, or a related page. Suppose we have defined a page using @page with label mypage, then a tab with label "My Page" to this page would look as follows:</p>



<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="user" url="@ref mypage" title="My Page"/&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


<p>You can also group tabs together in a custom group using a tab with type "usergroup". The following example puts the above tabs in a user defined group with title "My Group":</p>



<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="usergroup" title="My Group"&gt;
      &lt;tab type="user" url="http://www.google.com" title="Google"/&gt;
      &lt;tab type="user" url="@ref mypage" title="My Page"/&gt;
    &lt;/tab&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


<p>Groups can be nested to form a hierarchy.</p>


<p>By default a usergroup entry in the navigation tree is a link to a landing page with the contents of the group. You can link to a different page using the <span class="doxyComputerOutput">url</span> attribute just like you can for the <span class="doxyComputerOutput">&lt;tab&gt;</span> element and prevent any link using <span class="doxyComputerOutput">url="[none]"</span>, i.e.</p>



<pre><code>   &lt;tab type="usergroup" title="Group without link" url="[none]"&gt;
   ...
   &lt;/tab&gt;
</code></pre>


<p>The elements after <span class="doxyComputerOutput">navindex</span> represent the layout of the different pages generated by Doxygen:</p>


<ul class="doxyList ">
<li>The <span class="doxyComputerOutput">class</span> element represents the layout of all pages generated for documented classes, structs, unions, and interfaces.</li>
<li>The <span class="doxyComputerOutput">namespace</span> element represents the layout of all pages generated for documented namespaces (and also Java packages).</li>
<li>The <span class="doxyComputerOutput">concept</span> element represents the layout of all pages generated for documented concepts.</li>
<li>The <span class="doxyComputerOutput">module</span> element represents the layout of all pages generated for documented C++ modules.</li>
<li>The <span class="doxyComputerOutput">file</span> element represents the layout of all pages generated for documented files.</li>
<li>The <span class="doxyComputerOutput">group</span> element represents the layout of all pages generated for documented groups (or topics).</li>
<li>The <span class="doxyComputerOutput">directory</span> element represents the layout of all pages generated for documented directories.</li>
</ul>

<p>Each XML element within one of the above page elements represents a certain piece of information. Some pieces can appear in each type of page, others are specific for a certain type of page. Doxygen will list the pieces in the order in which they appear in the XML file.</p>


<p>The following generic elements are possible for each page:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">briefdescription</span></dt>
<dd><p>Represents the brief description on a page.</p></dd>
<dt><span class="doxyComputerOutput">detaileddescription</span></dt>
<dd><p>Represents the detailed description on a page.</p></dd>
</dl>

<p>The following generic element is possible for each page except the <span class="doxyComputerOutput">directory</span> page:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">authorsection</span></dt>
<dd><p>Represents the author section of a page (only used for man pages). This is a separate section for man pages with a text like: <span class="doxyComputerOutput">Generated automatically by Doxygen for My Project from the source code.</span> This should not be misinterpreted with the Doxygen commands <a href="/web-doxygen/docs/pages/commands/#cmdauthor">\author</a> or <a href="/web-doxygen/docs/pages/commands/#cmdauthors">\authors</a> that generate an author paragraph inside a detailed description.</p></dd>
</dl>

<p>The following generic element is possible for each page except the <span class="doxyComputerOutput">concept</span> page:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">memberdecl</span></dt>
<dd><p>Represents the quick overview of members on a page (member declarations). This elements has child elements per type of member list. The possible child elements are not listed in detail in the document, but the name of the element should be a good indication of the type of members that the element represents.</p></dd>
</dl>

<p>The following generic element is possible for each page except the <span class="doxyComputerOutput">concept</span> and <span class="doxyComputerOutput">module</span> page:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">memberdef</span></dt>
<dd><p>Represents the detailed member list on a page (member definition). Like the <span class="doxyComputerOutput">memberdecl</span> element, also this element has a number of possible child elements.</p></dd>
</dl>

<p>The <span class="doxyComputerOutput">class</span> page has the following specific elements:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">includes</span></dt>
<dd><p>Represents the include file needed to obtain the definition for this class.</p></dd>
<dt><span class="doxyComputerOutput">inheritancegraph</span></dt>
<dd><p>Represents the inheritance relations for a class. Note that the <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a> option determines if the inheritance relation is a list of base and derived classes or a graph.</p></dd>
<dt><span class="doxyComputerOutput">collaborationgraph</span></dt>
<dd><p>Represents the collaboration graph for a class.</p></dd>
<dt><span class="doxyComputerOutput">allmemberslink</span></dt>
<dd><p>Represents the link to the list of all members for a class.</p></dd>
<dt><span class="doxyComputerOutput">usedfiles</span></dt>
<dd><p>Represents the list of files from which documentation for the class was extracted.</p></dd>
</dl>

<p>The <span class="doxyComputerOutput">concept</span> page has the following specific elements:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">includes</span></dt>
<dd><p>Represents the include file needed to obtain the definition for this class.</p></dd>
<dt><span class="doxyComputerOutput">definition</span></dt>
<dd><p>Represents the definition of the concept</p></dd>
</dl>

<p>The <span class="doxyComputerOutput">file</span> page has the following specific elements:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">includes</span></dt>
<dd><p>Represents the list of #include statements contained in this file.</p></dd>
<dt><span class="doxyComputerOutput">includegraph</span></dt>
<dd><p>Represents the include dependency graph for the file.</p></dd>
<dt><span class="doxyComputerOutput">includedbygraph</span></dt>
<dd><p>Represents the included by dependency graph for the file.</p></dd>
<dt><span class="doxyComputerOutput">sourcelink</span></dt>
<dd><p>Represents the link to the source code of this file.</p></dd>
</dl>

<p>The <span class="doxyComputerOutput">module</span> page has a specific <span class="doxyComputerOutput">exportedmodules</span> element which represents the modules that are exported from this module.</p>


<p>The <span class="doxyComputerOutput">group</span> page has a specific <span class="doxyComputerOutput">groupgraph</span> element which represents the graph showing the dependencies between groups.</p>


<p>Similarly, the <span class="doxyComputerOutput">directory</span> page has a specific <span class="doxyComputerOutput">directorygraph</span> element which represents the graph showing the dependencies between the directories based on the #include relations of the files inside the directories.</p>


<p>Some elements have a <span class="doxyComputerOutput">visible</span> attribute which can be used to hide the fragment from the generated output, by setting the attribute's value to <span class="doxyComputerOutput">no</span>. You can also use the value of a configuration option to determine the visibility, by using its name prefixed with a dollar sign, e.g.</p>



<pre><code>  ...
  &lt;includes visible="$SHOW_INCLUDE_FILES"/&gt;
  ...
</code></pre>


<p>This was mainly added for backward compatibility. Note that the <span class="doxyComputerOutput">visible</span> attribute is just a hint for Doxygen. If no relevant information is available for a certain piece it is omitted even if it is set to <span class="doxyComputerOutput">yes</span> (i.e. no empty sections are generated).
<br/>
 Not all elements have a <span class="doxyComputerOutput">visible</span> attribute shown in the layout file, though this attribute can be used anyway (the default is <span class="doxyComputerOutput">visible="yes"</span>).</p>


<p>Some elements have a <span class="doxyComputerOutput">title</span> attribute. This attribute can be used to customize the title Doxygen will use as a header for the piece.</p>


<p>Note that as of doxygen version 1.13.1 and layout version 2.0, Doxygen will insert defaults for elements that are missing in the user defined layout file. This allows for the introduction of new elements, without having to update the user defined layout files to make them appear. For older Doxygen or layout versions, missing elements are treated as being invisible.</p>


## Using the XML output {#xmlgenerator}


<p>If the above two methods still do not provide enough flexibility, you can also use the XML output produced by Doxygen as a basis to generate the output you like. To do this set <a href="/web-doxygen/docs/pages/config/#cfg_generate_xml">GENERATE_XML</a> to <span class="doxyComputerOutput">YES</span>.</p>


<p>The XML output consists of an index file named <span class="doxyComputerOutput">index.xml</span> which lists all items extracted by Doxygen with references to the other XML files for details. The structure of the index is described by a schema file <span class="doxyComputerOutput">index.xsd</span>. All other XML files are described by the schema file named <span class="doxyComputerOutput">compound.xsd</span>. If you prefer one big XML file you can combine the index and the other files using the XSLT file <span class="doxyComputerOutput">combine.xslt</span>.</p>


<p>You can use any XML parser to parse the files or use the one that can be found in the <span class="doxyComputerOutput">addon/doxmlparser</span> directory of Doxygen's source distribution. Look at <span class="doxyComputerOutput">addon/doxmlparser/doxmlparser/index.py</span> and <span class="doxyComputerOutput">addon/doxmlparser/doxmlparser/compound.py</span> for the interface of the parser (it is generated by <a href="https://www.davekuhlman.org/generateDS.html">generatedDS</a> and follows the XML schema files <span class="doxyComputerOutput">index.xsd</span> and <span class="doxyComputerOutput">compound.xsd</span> found in <span class="doxyComputerOutput">templates/xml</span>). Look in <span class="doxyComputerOutput">addon/doxmlparser/examples</span> for examples.</p>


<p>The advantage of using the doxmlparser is that it allows you to only read the index file into memory and then only those XML files that you implicitly load via navigating through the index. As a result this works even for very large projects where reading all XML files as one big DOM tree would not fit into memory.</p>


<p>See <a href="https://github.com/breathe-doc/breathe">the Breathe project</a> for an example that uses Doxygen XML output from Python to bridge it with the <a href="http://www.sphinx-doc.org/en/stable/">Sphinx</a> document generator.</p>

 
Go to the <a href="/docs/pages/custcmd/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
