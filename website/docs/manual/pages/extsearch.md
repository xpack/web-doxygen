---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /pages/extsearch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# External Indexing and Searching




## Introduction {#extsearch_intro}


<p>With release 1.8.3, Doxygen provides the ability to search through HTML using an external indexing tool and search engine. This has several advantages:</p>


<ul class="doxyList ">
<li>For large projects it can have significant performance advantages over Doxygen's built-in search engine, as Doxygen uses a rather simple indexing algorithm.</li>
<li>It allows combining the search data of multiple projects into one index, allowing a global search across multiple Doxygen projects.</li>
<li>It allows adding additional data to the search index, i.e. other web pages not produced by Doxygen.</li>
<li>The search engine needs to run on a web server, but clients can still browse the web pages locally.</li>
</ul>

<p>To avoid that everyone has to start writing their own indexer and search engine, Doxygen provides an example tool for each action: <span class="doxyComputerOutput">doxyindexer</span> for indexing the data and <span class="doxyComputerOutput">doxysearch.cgi</span> for searching through the index.</p>


<p>The data flow is shown in the following diagram:</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/extsearch_flow.png"></img>
  <figcaption>External Search Data Flow</figcaption>
</figure></p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">doxygen</span> produces the raw search data</li>
<li><span class="doxyComputerOutput">doxyindexer</span> indexes the data into a search database <span class="doxyComputerOutput">doxysearch.db</span></li>
<li>when a user performs a search from a Doxygen generated HTML page, the CGI binary <span class="doxyComputerOutput">doxysearch.cgi</span> will be invoked.</li>
<li>the <span class="doxyComputerOutput">doxysearch.cgi</span> tool will perform a query on the database and return the results.</li>
<li>The browser will show the search results.</li>
</ul>

## Configuring {#extsearch_config}


<p>The first step is to make the search engine available via a web server. If you use <span class="doxyComputerOutput">doxysearch.cgi</span> this means making the <a href="https://en.wikipedia.org/wiki/Common_Gateway_Interface">CGI</a> binary available from the web server (i.e. be able to run it from a browser via an URL starting with http:)</p>


<p>How to setup a web server is outside the scope of this document, but if you for instance have Apache installed, you could simply copy the <span class="doxyComputerOutput">doxysearch.cgi</span> file from Doxygen's <span class="doxyComputerOutput">bin</span> directory to the <span class="doxyComputerOutput">cgi-bin</span> directory of the Apache web server. Read the <a href="https://httpd.apache.org/docs/2.2/howto/cgi.html">apache documentation</a> for details.</p>


<p>To test if <span class="doxyComputerOutput">doxysearch.cgi</span> is accessible start your web browser and point to URL to the binary and add <span class="doxyComputerOutput">?test</span> at the end</p>



<pre><code>http://yoursite.com/path/to/cgi/doxysearch.cgi?test
</code></pre>


<p>You should get the following message:</p>



<pre><code>Test failed: cannot find search index doxysearch.db
</code></pre>


<p>If you use Internet Explorer you may be prompted to download a file, which will then contain this message.</p>


<p>Since we didn't create or install a <span class="doxyComputerOutput">doxysearch.db</span> it is OK for the test to fail for this reason. How to correct this is discussed in the next section.</p>


<p>Before continuing with the next section add the above URL (without the <span class="doxyComputerOutput">?test</span> part) to the <a href="/web-doxygen/docs/pages/config/#cfg_searchengine_url">SEARCHENGINE_URL</a> tag in Doxygen's configuration file:</p>



<pre><code>SEARCHENGINE_URL = http://yoursite.com/path/to/cgi/doxysearch.cgi
</code></pre>


### Single project index {#extsearch_single}


<p>To use the external search option, make sure the following options are enabled in Doxygen's configuration file:</p>



<pre><code>SEARCHENGINE           = YES
SERVER_BASED_SEARCH    = YES
EXTERNAL_SEARCH        = YES
</code></pre>


<p>This will make Doxygen generate a file called <span class="doxyComputerOutput">searchdata.xml</span> in the output directory (configured with <a href="/web-doxygen/docs/pages/config/#cfg_output_directory">OUTPUT_DIRECTORY</a>). You can change the file name (and location) with the <a href="/web-doxygen/docs/pages/config/#cfg_searchdata_file">SEARCHDATA_FILE</a> option.</p>


<p>The next step is to put the raw search data into an index for efficient searching. You can use <span class="doxyComputerOutput">doxyindexer</span> for this. Simply run it from the command line:</p>



<pre><code>doxyindexer searchdata.xml
</code></pre>


<p>This will create a directory called <span class="doxyComputerOutput">doxysearch.db</span> with some files in it. By default the directory will be created at the location from which <span class="doxyComputerOutput">doxyindexer</span> was started, but you can change the directory using the <span class="doxyComputerOutput">-o</span> option.</p>


<p>Copy the <span class="doxyComputerOutput">doxysearch.db</span> directory to the same directory as where the <span class="doxyComputerOutput">doxysearch.cgi</span> is located and rerun the browser test by pointing the browser to</p>



<pre><code>http://yoursite.com/path/to/cgi/doxysearch.cgi?test
</code></pre>


<p>You should now get the following message:</p>



<pre><code>Test successful.
</code></pre>


<p>Now you should be able to search for words and symbols from the HTML output.</p>


### Multi project index {#extsearch_multi}


<p>In case you have more than one Doxygen project and these projects are related, it may be desirable to allow searching for words in all projects from within the documentation of any of the projects.</p>


<p>To make this possible all that is needed is to combine the search data for all projects into a single index, e.g. for two projects A and B for which the searchdata.xml is generated in directories project_A and project_B run:</p>



<pre><code>doxyindexer project_A/searchdata.xml project_B/searchdata.xml
</code></pre>


<p>and then copy the resulting <span class="doxyComputerOutput">doxysearch.db</span> to the directory where also <span class="doxyComputerOutput">doxysearch.cgi</span> is located.</p>


<p>The <span class="doxyComputerOutput">searchdata.xml</span> file doesn't contain any absolute paths or links, so how can the search results from multiple projects be linked back to the right documentation set? This is where the <a href="/web-doxygen/docs/pages/config/#cfg_external_search_id">EXTERNAL_SEARCH_ID</a> and <a href="/web-doxygen/docs/pages/config/#cfg_extra_search_mappings">EXTRA_SEARCH_MAPPINGS</a> options come into play.</p>


<p>To be able to identify the different projects, one needs to set a unique ID using <a href="/web-doxygen/docs/pages/config/#cfg_external_search_id">EXTERNAL_SEARCH_ID</a> for each project.</p>


<p>To link the search results to the right project, you need to define a mapping per project using the <a href="/web-doxygen/docs/pages/config/#cfg_extra_search_mappings">EXTRA_SEARCH_MAPPINGS</a> tag. With this option to can define the mapping from IDs of other projects to the (relative) location of documentation of those projects.</p>


<p>So for projects A and B the relevant part of the configuration file could look as follows:</p>



<pre><code>project_A/Doxyfile
------------------
EXTERNAL_SEARCH_ID    = A
EXTRA_SEARCH_MAPPINGS = B=../../project_B/html
</code></pre>


<p>for project A and for project B</p>



<pre><code>project_B/Doxyfile
------------------
EXTERNAL_SEARCH_ID    = B
EXTRA_SEARCH_MAPPINGS = A=../../project_A/html
</code></pre>


<p>with these settings, projects A and B can share the same search database, and the search results will link to the right documentation set.</p>


## Updating the index {#extsearch_update}


<p>When you modify the source code, you should re-run <span class="doxyComputerOutput">doxygen</span> to get up to date documentation again. When using external searching you also need to update the search index by re-running <span class="doxyComputerOutput">doxyindexer</span>. You could wrap the call to <span class="doxyComputerOutput">doxygen</span> and <span class="doxyComputerOutput">doxyindexer</span> together in a script to make this process easier.</p>


## Programming interface {#extsearch_api}


<p>Previous sections have assumed you use the tools <span class="doxyComputerOutput">doxyindexer</span> and <span class="doxyComputerOutput">doxysearch.cgi</span> to do the indexing and searching, but you could also write your own index and search tools if you like.</p>


<p>For this 3 interfaces are important</p>


<ul class="doxyList ">
<li>The format of the input for the index tool.</li>
<li>The format of the input for the search engine.</li>
<li>The format of the output of search engine.</li>
</ul>

<p>The next subsections describe these interfaces in more detail.</p>


### Indexer input format {#extsearch_api_index}


<p>The search data produced by Doxygen follows the <a href="https://cwiki.apache.org/confluence/display/solr/UpdateXmlMessages">Solr XML index message</a> format.</p>


<p>The input for the indexer is an XML file, which consists of one <span class="doxyComputerOutput">&lt;add&gt;</span> tag containing multiple <span class="doxyComputerOutput">&lt;doc&gt;</span> tags, which in turn contain multiple <span class="doxyComputerOutput">&lt;field&gt;</span> tags.</p>


<p>Here is an example of one doc node, which contains the search data and meta data for one method:</p>



<pre><code>&lt;add&gt;
  ...
  &lt;doc&gt;
    &lt;field name="type"&gt;function&lt;/field&gt;
    &lt;field name="name"&gt;QXmlReader::setDTDHandler&lt;/field&gt;
    &lt;field name="args"&gt;(QXmlDTDHandler *handler)=0&lt;/field&gt;
    &lt;field name="tag"&gt;qtools.tag&lt;/field&gt;
    &lt;field name="url"&gt;de/df6/class_q_xml_reader.html#a0b24b1fe26a4c32a8032d68ee14d5dba&lt;/field&gt;
    &lt;field name="keywords"&gt;setDTDHandler QXmlReader::setDTDHandler QXmlReader&lt;/field&gt;
    &lt;field name="text"&gt;Sets the DTD handler to handler DTDHandler()&lt;/field&gt;
  &lt;/doc&gt;
  ...
&lt;/add&gt;
</code></pre>


<p>Each field has a name. The following field names are supported:</p>


<ul class="doxyList ">
<li><em>type</em>: the type of the search entry; can be one of: source, function, slot, signal, variable, typedef, enum, enumvalue, property, event, related, friend, define, file, namespace, concept, group, package, page, dir, module, constants, library, type, union, interface, protocol category, exception, class, struct, service, singleton</li>
<li><em>name</em>: the name of the search entry; for a method this is the qualified name of the method, for a class it is the name of the class, etc.</li>
<li><em>args</em>: the parameter list (in case of functions or methods)</li>
<li><em>tag</em>: the name of the tag file used for this project.</li>
<li><em>url</em>: the (relative) URL to the HTML documentation for this entry.</li>
<li><em>keywords</em>: important words that are representative for the entry. When searching for such keyword, this entry should get a higher rank in the search results.</li>
<li><em>text</em>: the documentation associated with the item. Note that only words are present, no markup.</li>
</ul>


:::info
<p>Due to the potentially large size of the XML file, it is recommended to use a <a href="https://en.wikipedia.org/wiki/Simple_API_for_XML">SAX based parser</a> to process it.</p>
:::


### Search URL format {#extsearch_api_search_in}


<p>When the search engine is invoked from a Doxygen generated HTML page, a number of parameters are passed to via the <a href="https://en.wikipedia.org/wiki/Query_string">query string</a>.</p>


<p>The following fields are passed:</p>


<ul class="doxyList ">
<li><em>q</em>: the query text as entered by the user</li>
<li><em>n</em>: the number of search results requested.</li>
<li><em>p</em>: the number of search page for which to return the results. Each page has <em>n</em> values.</li>
<li><em>cb</em>: the name of the callback function, used for JSON with padding, see the next section.</li>
</ul>

<p>From the complete list of search results, the range <span class="doxyComputerOutput">[n*p - n*(p+1)-1]</span> should be returned.</p>


<p>Here is an example of how a query looks like.</p>



<pre><code>http://yoursite.com/path/to/cgi/doxysearch.cgi?q=list&amp;n=20&amp;p=1&amp;cb=dummy
</code></pre>


<p>It represents a query for the word 'list' (<span class="doxyComputerOutput">q=list</span>) requesting 20 search results (<span class="doxyComputerOutput">n=20</span>), starting with the result number 20 (<span class="doxyComputerOutput">p=1</span>) and using callback 'dummy' (<span class="doxyComputerOutput">cb=dummy</span>):</p>



:::info
<p>The values are <a href="https://en.wikipedia.org/wiki/Percent-encoding">URL encoded</a> so they have to be decoded before they can be used.</p>
:::


### Search results format {#extsearch_api_search_out}


<p>When invoking the search engine as shown in the previous subsection, it should reply with the results. The format of the reply is <a href="https://en.wikipedia.org/wiki/JSONP">JSON with padding</a>, which is basically a JavaScript struct wrapped in a function call. The name of function should be the name of the callback (as passed with the <em>cb</em> field in the query).</p>


<p>With the example query as shown the previous subsection the main structure of the reply should look as follows:</p>



<pre><code>dummy({
  "hits":179,
  "first":20,
  "count":20,
  "page":1,
  "pages":9,
  "query": "list",
  "items":[
  ...
 ]})
</code></pre>


<p>The fields have the following meaning:</p>


<ul class="doxyList ">
<li><em>hits</em>: the total number of search results (could be more than was requested).</li>
<li><em>first</em>: the index of first result returned: <code>$\min(n*p,\mbox{\em hits})$</code>.</li>
<li><em>count</em>: the actual number of results returned: <code>$\min(n,\mbox{\em hits}-\mbox{\em first})$</code></li>
<li><em>page</em>: the page number of the result: <code>$p$</code></li>
<li><em>pages</em>: the total number of pages: <code>$\left\lceil\frac{\mbox{\em hits}}{n}\right\rceil$</code>.</li>
<li><em>items</em>: an array containing the search data per result.</li>
</ul>

<p>Here is an example of how the element of the <em>items</em> array should look like:</p>



<pre><code>{"type": "function",
 "name": "QDir::entryInfoList(const QString &amp;nameFilter, int filterSpec=DefaultFilter, int sortSpec=DefaultSort) const",
 "tag": "qtools.tag",
 "url": "d5/d8d/class_q_dir.html#a9439ea6b331957f38dbad981c4d050ef",
 "fragments":[
   "Returns a &lt;span class=\"hl\"&gt;list&lt;/span&gt; of QFileInfo objects for all files and directories...",
   "... pointer to a QFileInfoList The &lt;span class=\"hl\"&gt;list&lt;/span&gt; is owned by the QDir object...",
   "... to keep the entries of the &lt;span class=\"hl\"&gt;list&lt;/span&gt; after a subsequent call to this..."
 ]
},
</code></pre>


<p>The fields for such an item have the following meaning:</p>


<ul class="doxyList ">
<li><em>type</em>: the type of the item, as found in the field with name "type" in the raw search data.</li>
<li><em>name</em>: the name of the item, including the parameter list, as found in the fields with name "name" and "args" in the raw search data.</li>
<li><em>tag</em>: the name of the tag file, as found in the field with name "tag" in the raw search data.</li>
<li><em>url</em>: the name of the (relative) URL to the documentation, as found in the field with name "url" in the raw search data.</li>
<li>"fragments": an array with 0 or more fragments of text containing words that have been search for. These words should be wrapped in <span class="doxyComputerOutput">&lt;span class="hl"&gt;</span> and <span class="doxyComputerOutput">&lt;/span&gt;</span> tags to highlight them in the output.</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
