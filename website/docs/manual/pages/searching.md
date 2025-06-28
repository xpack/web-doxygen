---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/searching
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Searching




<p>Doxygen indexes your source code in various ways to make it easier to navigate and find what you are looking for. There are also situations however where you want to search for something by keyword rather than browse for it.</p>

<p>HTML browsers by default have no search capabilities that work across multiple pages, so either Doxygen or external tools need to help to facilitate this feature.</p>

<p>Doxygen has 7 different ways to add searching to the HTML output, each of which has its own advantages and disadvantages:</p>

## 1. Client side searching

<p>The easiest way to enable searching is to enable the built-in client side search engine. This engine is implemented using JavaScript and DHTML only and runs entirely on the clients browser. So no additional tooling is required to make it work.</p>

<p>To enable it set <a href="/web-doxygen/docs/pages/config/#cfg_searchengine">SEARCHENGINE</a> to <span class="doxyComputerOutput">YES</span> in the configuration file and make sure <a href="/web-doxygen/docs/pages/config/#cfg_server_based_search">SERVER_BASED_SEARCH</a> is set to <span class="doxyComputerOutput">NO</span>.</p>

<p>An additional advantage of this method is that it provides live searching, i.e. the search results are presented and adapted as you type.</p>

<p>This method also has its drawbacks: it is limited to searching for symbols only. It does not provide full text search capabilities and it does not scale well to very large projects (then searching becomes very slow). Furthermore the searching is done from the beginning of the indexed items, so when having the available items <span class="doxyComputerOutput">A_STRING</span>, <span class="doxyComputerOutput">AA_STRING</span> and <span class="doxyComputerOutput">STRING</span> and typing in the search box <span class="doxyComputerOutput">A</span> it will find <span class="doxyComputerOutput">A_STRING</span> and <span class="doxyComputerOutput">AA_STRING</span>, but when typing e.g. <span class="doxyComputerOutput">STR</span> it will only find <span class="doxyComputerOutput">STRING</span> and not <span class="doxyComputerOutput">A_STRING</span>.</p>

## 2. Server side searching

<p>If you plan to put the HTML documentation on a web server, and that web server has the capability to process PHP code, then you can also use Doxygen's built-in server side search engine.</p>

<p>To enable this set both <a href="/web-doxygen/docs/pages/config/#cfg_searchengine">SEARCHENGINE</a> and <a href="/web-doxygen/docs/pages/config/#cfg_server_based_search">SERVER_BASED_SEARCH</a> to <span class="doxyComputerOutput">YES</span> in the configuration file and set <a href="/web-doxygen/docs/pages/config/#cfg_external_search">EXTERNAL_SEARCH</a> to <span class="doxyComputerOutput">NO</span>.</p>

<p>Advantages over the client side search engine are that it provides full text search and it scales well to medium side projects.</p>

<p>Disadvantages are that it does not work locally (i.e. using a "file://" URL) and that it does not provide live search capabilities.</p>

:::info
<p>In the future this option will probably be replaced by the next search option.</p>
:::


## 3. Server side searching with external indexing

<p>With release 1.8.3 of Doxygen, another server based search option has been added. With this option Doxygen generates the raw data that can be searched and leaves it up to external tools to do the indexing and searching, meaning that you could use your own indexer and search engine of choice. To make life easier Doxygen ships with an example indexer (doxyindexer) and search engine (doxysearch.cgi) based on the <a href="https://xapian.org/">Xapian</a> open source search engine library. Both binaries are included in the distribution but not installed by default; they can be manually copied from the <span class="doxyComputerOutput">bin</span> folder to i.e. <span class="doxyComputerOutput">/usr/local/bin</span> or <span class="doxyComputerOutput">/var/www/cgi-bin</span> as desired.</p>

<p>To enable this search method set <a href="/web-doxygen/docs/pages/config/#cfg_searchengine">SEARCHENGINE</a>, <a href="/web-doxygen/docs/pages/config/#cfg_server_based_search">SERVER_BASED_SEARCH</a> and <a href="/web-doxygen/docs/pages/config/#cfg_external_search">EXTERNAL_SEARCH</a> all to <span class="doxyComputerOutput">YES</span>.</p>

<p>See <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for configuration details.</p>

<p>Advantages over option 2 are that this method (potentially) scales to very large projects. It is also possible to combine multiple Doxygen projects and external data into one search index. The way the interaction with the search engine is done, makes it possible to search from local HTML pages. Also the search results have better ranking and show context information (if available).</p>

<p>Disadvantages are that is requires a web server that can execute a CGI binary, and an additional indexing step after running Doxygen.</p>

## 4. Windows Compiled HTML Help

<p>If you are running Doxygen on Windows, then you can make a compiled HTML Help file (.chm) out of the HTML files produced by Doxygen. This is a single file containing all HTML files and it also includes a search index. There are viewers for this format on many platforms, and Windows even supports it natively.</p>

<p>To enable this set <a href="/web-doxygen/docs/pages/config/#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> to <span class="doxyComputerOutput">YES</span> in the configuration file. To let Doxygen compile the HTML Help file for you, you also need to specify the path to the HTML compiler (hhc.exe) using the <a href="/web-doxygen/docs/pages/config/#cfg_hhc_location">HHC_LOCATION</a> configuration option and the name of the resulting CHM file using <a href="/web-doxygen/docs/pages/config/#cfg_chm_file">CHM_FILE</a>.</p>

<p>An advantage of this method is that the result is a single file that can easily be distributed. It also provides full text search.</p>

<p>Disadvantages are that compiling the CHM file only works on Windows and requires Microsoft's HTML compiler, which is not very actively supported by Microsoft. Although the tool works fine for most people, it can sometimes crash for no apparent reason (how typical).</p>

## 5. macOS Doc Sets

<p>If you are running Doxygen on macOS 10.5 or higher, then you can make a "doc set" out of the HTML files produced by Doxygen. A doc set consists of a single directory with a special structure containing the HTML files along with a precompiled search index. A doc set can be embedded in Xcode (the integrated development environment provided by Apple).</p>

<p>To enable the creation of doc sets set <a href="/web-doxygen/docs/pages/config/#cfg_generate_docset">GENERATE_DOCSET</a> to <span class="doxyComputerOutput">YES</span> in the configuration file. There are a couple of other doc set related options you may want to set. After Doxygen has finished you will find a Makefile in the HTML output directory. Running "make install" on this Makefile will compile and install the doc set. See <a href="https://developer.apple.com/library/archive/featuredarticles/DoxygenXcode/_index.html">this article</a> for more info.</p>

<p>Advantage of this method is that it nicely integrates with the Xcode development environment, allowing for instance to click on an identifier in the editor and jump to the corresponding section in the Doxygen documentation.</p>

<p>Disadvantage is that it only works in combination with Xcode on macOS.</p>

## 6. Qt Compressed Help

<p>If you develop for or want to install the Qt application framework, you will get an application called <a href="https://doc.qt.io/archives/qt-4.8/assistant-manual.html">Qt assistant</a>. This is a help viewer for Qt Compressed Help files (<span class="doxyComputerOutput">.qch</span>).</p>

<p>To enable this feature set <a href="/web-doxygen/docs/pages/config/#cfg_generate_qhp">GENERATE_QHP</a> to <span class="doxyComputerOutput">YES</span>. You also need to fill in the other Qt help related options, such as <a href="/web-doxygen/docs/pages/config/#cfg_qhp_namespace">QHP_NAMESPACE</a>, <a href="/web-doxygen/docs/pages/config/#cfg_qhg_location">QHG_LOCATION</a>, <a href="/web-doxygen/docs/pages/config/#cfg_qhp_virtual_folder">QHP_VIRTUAL_FOLDER</a>. See <a href="https://doc.qt.io/archives/qq/qq28-qthelp.html#htmlfilesandhelpprojects">this article</a> for more info.</p>

<p>Feature wise the Qt compressed help feature is comparable with the CHM output, with the additional advantage that compiling the QCH file is not limited to Windows.</p>

<p>Disadvantage is that it requires setting up a Qt 4.5 (or better) for each user, or distributing the Qt help assistant along with the documentation, which is complicated by the fact that it is not available as a separate package at this moment.</p>

## 7. Eclipse Help Plugin

<p>If you use eclipse, you can embed the documentation generated by Doxygen as a help plugin. It will then appear as a topic in the help browser that can be started from "Help contents" in the Help menu. Eclipse will generate a search index for the documentation when you first search for a keyword.</p>

<p>To enable the help plugin set <a href="/web-doxygen/docs/pages/config/#cfg_generate_eclipsehelp">GENERATE_ECLIPSEHELP</a> to <span class="doxyComputerOutput">YES</span>, and define a unique identifier for your project via <a href="/web-doxygen/docs/pages/config/#cfg_eclipse_doc_id">ECLIPSE_DOC_ID</a>, i.e.:</p>


<pre><code>GENERATE_ECLIPSEHELP = YES
   ECLIPSE_DOC_ID       = com.yourcompany.yourproject
</code></pre>


<p>then create the <span class="doxyComputerOutput">com.yourcompany.yourproject</span> directory (so with the same name as the value of <span class="doxyComputerOutput">ECLIPSE_DOC_ID</span>) in the <span class="doxyComputerOutput">plugin</span> directory of eclipse and after Doxygen completes copy to contents of the help output directory to the <span class="doxyComputerOutput">com.yourcompany.yourproject</span> directory. Then restart eclipse to make let it find the new plugin.</p>

<p>The eclipse help plugin provides similar functionality as the Qt compressed help or CHM output, but it does require that Eclipse is installed and running.</p>
 
Go to the <a href="/docs/pages/customize/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
