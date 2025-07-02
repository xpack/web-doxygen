---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/customize
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Customizing the output




Doxygen provides various levels of customization. The section <a href="#minor_tweaks">Minor Tweaks</a> discusses what to do if you want to do minor tweaking to the look and feel of the output. The section <a href="#layout">Layout</a> show how to reorder and hide certain information on a page. The section <a href="#xmlgenerator">XML output</a> show how to generate whatever output you want based on the XML output produced by Doxygen.

## Minor Tweaks {#minor_tweaks}


The next subsections describe some aspects that can be tweaked with little effort.

### Overall Color {#minor_tweaks_colors}


To change the overall color of the HTML output Doxygen provides three options

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_hue">HTML_COLORSTYLE_HUE</a></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_sat">HTML_COLORSTYLE_SAT</a></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_colorstyle_gamma">HTML_COLORSTYLE_GAMMA</a></li>
</ul>

to change the hue, saturation, and gamma correction of the colors respectively.

For your convenience the GUI frontend <a href="/web-doxygen/docs/pages/doxywizard-usage">Doxywizard</a> has a control that allows you to see the effect of changing the values of these options on the output in real time.

### Navigation {#minor_tweaks_treeview}


By default, Doxygen will show a title area spanning the full width of the page and below the contents with a navigation tree as a sidebar on the left hand side of each HTML page.

This corresponds to the following settings in the Doxyfile:

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <code>NO</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_treeview.png"></img>
</figure>

you can make the side bar span the whole height of the page using

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <code>YES</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_sidebar.png"></img>
</figure>

you can also replace the navigation tree by tabs on top of every HTML page, corresponding to the following settings:

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>NO</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>NO</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_notreeview.png"></img>
</figure>

or even have both forms of navigation:

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>NO</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <code>NO</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_treeview.png"></img>
</figure>

and this also works with the side bar spanning the full height

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>NO</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_full_sidebar">FULL_SIDEBAR</a> = <code>YES</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_index_and_sidebar.png"></img>
</figure>

if you already use an external index (i.e. have one of the following options enabled <a href="/web-doxygen/docs/pages/config/#cfg_generate_htmlhelp">GENERATE\_HTMLHELP</a>, <a href="/web-doxygen/docs/pages/config/#cfg_generate_eclipsehelp">GENERATE\_ECLIPSEHELP</a>, <a href="/web-doxygen/docs/pages/config/#cfg_generate_qhp">GENERATE\_QHP</a>, or <a href="/web-doxygen/docs/pages/config/#cfg_generate_docset">GENERATE\_DOCSET</a>) then you can also disable all indices, like so:

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE_INDEX</a> = <code>YES</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> = <code>NO</code></li>
</ul>

<figure>
  <img src="/web-doxygen/img/doxygen-manual/layout_noindex_and_notreeview.png"></img>
</figure>

### Dynamic Content {#minor_tweaks_dynsection}


To make the HTML output more interactive, Doxygen provides a number of options that are disabled by default:

<ul class="doxyList ">
<li>enabling <a href="/web-doxygen/docs/pages/config/#cfg_html_dynamic_sections">HTML_DYNAMIC_SECTIONS</a> will make Doxygen hide certain content (like graphs) in the HTML by default, and let the reader expand these sections on request.</li>
<li>enabling <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> along with <a href="/web-doxygen/docs/pages/config/#cfg_interactive_svg">INTERACTIVE_SVG</a> while setting <a href="/web-doxygen/docs/pages/config/#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> to <code>svg</code>, will make Doxygen produce SVG images that will allow the user to zoom and pan (this only happens when the size of the images exceeds a certain size).</li>
</ul>

### Header, Footer, and Stylesheet changes {#minor_tweaks_header_css}


To tweak things like fonts or colors, margins, or other look &amp; feel aspects of the HTML output in detail, you can create a different <a href="https://www.w3schools.com/css/default.asp">cascading style sheet</a>. You can also let Doxygen use a custom header and footer for each HTML page it generates, for instance to make the output conform to the style used on the rest of your web site.

To do this first run Doxygen as follows:


<pre><code>doxygen -w html header.html footer.html customdoxygen.css
</code></pre>


This will create 3 files:

<ul class="doxyList ">
<li>header.html is a HTML fragment which Doxygen normally uses to start a HTML page. Note that the fragment ends with a body tag and that is contains a couple of commands of the form $word. These will be replaced by Doxygen on the fly.</li>
<li>footer.html is a HTML fragment which Doxygen normally uses to end a HTML page. Also here special commands can be used. This file contain the link to www.doxygen.org and the body and html end tags.</li>
<li>customdoxygen.css is the default cascading style sheet used by Doxygen. It is recommended only to look into this file and overrule some settings you like by putting them in a separate stylesheets and referencing those extra files via <a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a>.</li>
</ul>

You should edit these files and then reference them from the configuration file.

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML_HEADER</a> = <code>header.html</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_footer">HTML_FOOTER</a> = <code>footer.html</code></li>
<li><a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> = <code>my_customdoxygen.css</code></li>
</ul>

:::info
it is not longer recommended to use <a href="/web-doxygen/docs/pages/config/#cfg_html_stylesheet">HTML\_STYLESHEET</a>, as it make it difficult to upgrade to a newer version of Doxygen. Use <a href="/web-doxygen/docs/pages/config/#cfg_html_extra_stylesheet">HTML\_EXTRA\_STYLESHEET</a> instead.
:::


See the documentation of the <a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML\_HEADER</a> tag for more information about the possible meta commands you can use inside your custom header.

:::info
You should not put the style sheet in the HTML output directory. Treat it as a source file. Doxygen will copy it for you.
:::


:::info
If you use images or other external content in a custom header you need to make sure these end up in the HTML output directory yourself, for instance by writing a script that runs Doxygen can then copies the images to the output.
:::


:::warning
The structure of headers and footers may change after upgrading to a newer version of Doxygen, so if you are using a custom header or footer, it might not produce valid output anymore after upgrading.
:::


## Changing the layout of pages {#layout}


In some cases you may want to change the way the output is structured. A different style sheet or custom headers and footers do not help in such case.

The solution Doxygen provides is a layout file, which you can modify and Doxygen will use to control what information is presented, in which order, and to some extent also how information is presented. The layout file is an XML file.

The default layout can be generated by Doxygen using the following command:


<pre><code>doxygen -l
</code></pre>


optionally the name of the layout file can be specified, if omitted <code>DoxygenLayout.xml</code> will be used.

The next step is to mention the layout file in the configuration file (see also <a href="/web-doxygen/docs/pages/config/#cfg_layout_file">LAYOUT\_FILE</a>)


<pre><code>LAYOUT_FILE = DoxygenLayout.xml
</code></pre>


To change the layout all you need to do is edit the layout file.

The toplevel structure of the file looks as follows:


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


The root element of the XML file is <code>doxygenlayout</code>, it has an attribute named <code>version</code>, which will be used in the future to cope with changes that are not backward compatible.

The first section, identified by the <code>navindex</code> element, represents the layout of the navigation tabs displayed at the top of each HTML page. At the same time it also controls the items in the navigation tree in case <a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE\_TREEVIEW</a> is enabled. Each tab is represented by a <code>tab</code> element in the XML file.

You can hide tabs by setting the <code>visible</code> attribute to <code>no</code>. You can also override the default title of a tab by specifying it as the value of the <code>title</code> attribute. If the title field is the empty string (the default) then Doxygen will fill in an appropriate language specific title.

You can reorder the tabs by moving the tab elements in the XML file within the <code>navindex</code> element and even change the tree structure. Do not change the value of the <code>type</code> attribute however. Only a fixed set of types are supported, each representing a link to a specific index.

You can also add custom tabs using a type with name "user". Here is an example that shows how to add a tab with title "Google" pointing to www.google.com:


<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="user" url="http://www.google.com" title="Google"/&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


The url field can also be a relative URL. If the URL starts with @ref the link will point to a documented entities, such as a class, a function, a group, or a related page. Suppose we have defined a page using @page with label mypage, then a tab with label "My Page" to this page would look as follows:


<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="user" url="@ref mypage" title="My Page"/&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


You can also group tabs together in a custom group using a tab with type "usergroup". The following example puts the above tabs in a user defined group with title "My Group":


<pre><code>  &lt;navindex&gt;
    ...
    &lt;tab type="usergroup" title="My Group"&gt;
      &lt;tab type="user" url="http://www.google.com" title="Google"/&gt;
      &lt;tab type="user" url="@ref mypage" title="My Page"/&gt;
    &lt;/tab&gt;
    ...
  &lt;/navindex&gt;
</code></pre>


Groups can be nested to form a hierarchy.

By default a usergroup entry in the navigation tree is a link to a landing page with the contents of the group. You can link to a different page using the <code>url</code> attribute just like you can for the <code>&lt;tab&gt;</code> element and prevent any link using <code>url="\[none\]"</code>, i.e.


<pre><code>   &lt;tab type="usergroup" title="Group without link" url="[none]"&gt;
   ...
   &lt;/tab&gt;
</code></pre>


The elements after <code>navindex</code> represent the layout of the different pages generated by Doxygen:

<ul class="doxyList ">
<li>The <code>class</code> element represents the layout of all pages generated for documented classes, structs, unions, and interfaces.</li>
<li>The <code>namespace</code> element represents the layout of all pages generated for documented namespaces (and also Java packages).</li>
<li>The <code>concept</code> element represents the layout of all pages generated for documented concepts.</li>
<li>The <code>module</code> element represents the layout of all pages generated for documented C++ modules.</li>
<li>The <code>file</code> element represents the layout of all pages generated for documented files.</li>
<li>The <code>group</code> element represents the layout of all pages generated for documented groups (or topics).</li>
<li>The <code>directory</code> element represents the layout of all pages generated for documented directories.</li>
</ul>

Each XML element within one of the above page elements represents a certain piece of information. Some pieces can appear in each type of page, others are specific for a certain type of page. Doxygen will list the pieces in the order in which they appear in the XML file.

The following generic elements are possible for each page:

<dl class="doxyVariableList">
<dt><code>briefdescription</code></dt>
<dd>Represents the brief description on a page.</dd>
<dt><code>detaileddescription</code></dt>
<dd>Represents the detailed description on a page.</dd>
</dl>

The following generic element is possible for each page except the <code>directory</code> page:

<dl class="doxyVariableList">
<dt><code>authorsection</code></dt>
<dd>Represents the author section of a page (only used for man pages). This is a separate section for man pages with a text like: <code>Generated automatically by Doxygen for My Project from the source code.</code> This should not be misinterpreted with the Doxygen commands <a href="/web-doxygen/docs/pages/commands/#cmdauthor">\author</a> or <a href="/web-doxygen/docs/pages/commands/#cmdauthors">\authors</a> that generate an author paragraph inside a detailed description.</dd>
</dl>

The following generic element is possible for each page except the <code>concept</code> page:

<dl class="doxyVariableList">
<dt><code>memberdecl</code></dt>
<dd>Represents the quick overview of members on a page (member declarations). This elements has child elements per type of member list. The possible child elements are not listed in detail in the document, but the name of the element should be a good indication of the type of members that the element represents.</dd>
</dl>

The following generic element is possible for each page except the <code>concept</code> and <code>module</code> page:

<dl class="doxyVariableList">
<dt><code>memberdef</code></dt>
<dd>Represents the detailed member list on a page (member definition). Like the <code>memberdecl</code> element, also this element has a number of possible child elements.</dd>
</dl>

The <code>class</code> page has the following specific elements:

<dl class="doxyVariableList">
<dt><code>includes</code></dt>
<dd>Represents the include file needed to obtain the definition for this class.</dd>
<dt><code>inheritancegraph</code></dt>
<dd>Represents the inheritance relations for a class. Note that the <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a> option determines if the inheritance relation is a list of base and derived classes or a graph.</dd>
<dt><code>collaborationgraph</code></dt>
<dd>Represents the collaboration graph for a class.</dd>
<dt><code>allmemberslink</code></dt>
<dd>Represents the link to the list of all members for a class.</dd>
<dt><code>usedfiles</code></dt>
<dd>Represents the list of files from which documentation for the class was extracted.</dd>
</dl>

The <code>concept</code> page has the following specific elements:

<dl class="doxyVariableList">
<dt><code>includes</code></dt>
<dd>Represents the include file needed to obtain the definition for this class.</dd>
<dt><code>definition</code></dt>
<dd>Represents the definition of the concept</dd>
</dl>

The <code>file</code> page has the following specific elements:

<dl class="doxyVariableList">
<dt><code>includes</code></dt>
<dd>Represents the list of #include statements contained in this file.</dd>
<dt><code>includegraph</code></dt>
<dd>Represents the include dependency graph for the file.</dd>
<dt><code>includedbygraph</code></dt>
<dd>Represents the included by dependency graph for the file.</dd>
<dt><code>sourcelink</code></dt>
<dd>Represents the link to the source code of this file.</dd>
</dl>

The <code>module</code> page has a specific <code>exportedmodules</code> element which represents the modules that are exported from this module.

The <code>group</code> page has a specific <code>groupgraph</code> element which represents the graph showing the dependencies between groups.

Similarly, the <code>directory</code> page has a specific <code>directorygraph</code> element which represents the graph showing the dependencies between the directories based on the #include relations of the files inside the directories.

Some elements have a <code>visible</code> attribute which can be used to hide the fragment from the generated output, by setting the attribute's value to <code>no</code>. You can also use the value of a configuration option to determine the visibility, by using its name prefixed with a dollar sign, e.g.


<pre><code>  ...
  &lt;includes visible="$SHOW_INCLUDE_FILES"/&gt;
  ...
</code></pre>


This was mainly added for backward compatibility. Note that the <code>visible</code> attribute is just a hint for Doxygen. If no relevant information is available for a certain piece it is omitted even if it is set to <code>yes</code> (i.e. no empty sections are generated).
<br/>
 Not all elements have a <code>visible</code> attribute shown in the layout file, though this attribute can be used anyway (the default is <code>visible="yes"</code>).

Some elements have a <code>title</code> attribute. This attribute can be used to customize the title Doxygen will use as a header for the piece.

Note that as of doxygen version 1.13.1 and layout version 2.0, Doxygen will insert defaults for elements that are missing in the user defined layout file. This allows for the introduction of new elements, without having to update the user defined layout files to make them appear. For older Doxygen or layout versions, missing elements are treated as being invisible.

## Using the XML output {#xmlgenerator}


If the above two methods still do not provide enough flexibility, you can also use the XML output produced by Doxygen as a basis to generate the output you like. To do this set <a href="/web-doxygen/docs/pages/config/#cfg_generate_xml">GENERATE\_XML</a> to <code>YES</code>.

The XML output consists of an index file named <code>index.xml</code> which lists all items extracted by Doxygen with references to the other XML files for details. The structure of the index is described by a schema file <code>index.xsd</code>. All other XML files are described by the schema file named <code>compound.xsd</code>. If you prefer one big XML file you can combine the index and the other files using the XSLT file <code>combine.xslt</code>.

You can use any XML parser to parse the files or use the one that can be found in the <code>addon/doxmlparser</code> directory of Doxygen's source distribution. Look at <code>addon/doxmlparser/doxmlparser/index.py</code> and <code>addon/doxmlparser/doxmlparser/compound.py</code> for the interface of the parser (it is generated by <a href="https://www.davekuhlman.org/generateDS.html">generatedDS</a> and follows the XML schema files <code>index.xsd</code> and <code>compound.xsd</code> found in <code>templates/xml</code>). Look in <code>addon/doxmlparser/examples</code> for examples.

The advantage of using the doxmlparser is that it allows you to only read the index file into memory and then only those XML files that you implicitly load via navigating through the index. As a result this works even for very large projects where reading all XML files as one big DOM tree would not fit into memory.

See <a href="https://github.com/breathe-doc/breathe">the Breathe project</a> for an example that uses Doxygen XML output from Python to bridge it with the <a href="http://www.sphinx-doc.org/en/stable/">Sphinx</a> document generator.
 
Go to the <a href="/docs/pages/custcmd/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
