---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /pages/doxygen-usage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Doxygen usage




<p>Doxygen is a command line based utility. Calling <span class="doxyComputerOutput">doxygen</span> with the <span class="doxyComputerOutput">--help</span> option at the command line will give you a brief description of the usage of the program.</p>


<p>All options consist of a leading character <span class="doxyComputerOutput">-</span>, followed by one character and one or more arguments depending on the option.</p>


<p>To generate a manual for your project you typically need to follow these steps:</p>


<ol class="doxyList" type="1">
<li>You document your source code with special documentation blocks (see section <a href="/web-doxygen/docs/pages/docblocks/#specialblock">Special comment blocks</a>).</li>
<li>You generate a configuration file (see section <a href="/web-doxygen/docs/pages/config">Configuration</a>) by calling Doxygen with the <span class="doxyComputerOutput">-g</span> option:


<pre><code>doxygen -g &lt;config_file&gt;
</code></pre></li>
<li>You edit the configuration file so it matches your project. In the configuration file you can specify the input files and a lot of optional information.</li>
<li>You let Doxygen generate the documentation, based on the settings in the configuration file:


<pre><code>doxygen &lt;config_file&gt;
</code></pre></li>
</ol>

<p>If you have a configuration file generated with an older version of Doxygen, you can upgrade it to the current version by running Doxygen with the -u option.</p>



<pre><code>doxygen -u &lt;config_file&gt;
</code></pre>


<p>All configuration settings in the original configuration file will be copied to the new configuration file. Any new options will have their default value. Note that comments that you may have added in the original configuration file will be lost.</p>


## Fine-tuning the output {#doxygen_finetune}


<p>If you want to fine-tune the way the output looks, Doxygen allows you generate default style sheet, header, and footer files that you can edit afterwards:</p>


<ul class="doxyList ">
<li>For HTML output, you can generate the default header file (see <a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML_HEADER</a>), the default footer (see <a href="/web-doxygen/docs/pages/config/#cfg_html_footer">HTML_FOOTER</a>), and the default style sheet (see <a href="/web-doxygen/docs/pages/config/#cfg_html_stylesheet">HTML_STYLESHEET</a>), using the following command:


<pre><code>doxygen -w html header.html footer.html stylesheet.css &lt;config_file&gt;
</code></pre>


The <span class="doxyComputerOutput">config_file</span> is optional. When omitted Doxygen will search for a file named <span class="doxyComputerOutput">Doxyfile</span> and process that. When this is also not found it will used the default settings.

</li>
<li>For <code>{\LaTeX}</code> output, you can generate the first and last part of <span class="doxyComputerOutput">refman.tex</span> (see <a href="/web-doxygen/docs/pages/config/#cfg_latex_header">LATEX_HEADER</a> and <a href="/web-doxygen/docs/pages/config/#cfg_latex_footer">LATEX_FOOTER</a>) and the style sheet included by that header (normally <span class="doxyComputerOutput">doxygen.sty</span>), using the following command:


<pre><code>doxygen -w latex header.tex footer.tex doxygen.sty &lt;config_file&gt;
</code></pre>


If you need non-default options (for instance to use extra <code>{\LaTeX}</code> packages) you need to make a configuration file with those options set correctly and then specify that configuration file after the generated files (make a backup of the configuration file first so you don't loose it in case you forget to specify one of the output files).</li>
<li>For RTF output, you can generate the default style sheet file (see <a href="/web-doxygen/docs/pages/config/#cfg_rtf_stylesheet_file">RTF_STYLESHEET_FILE</a>) using:


<pre><code>doxygen -w rtf rtfstyle.cfg
</code></pre></li>
</ul>


:::warning
<p>When using a custom header you are responsible for the proper inclusion of any scripts and style sheets that Doxygen needs, which is dependent on the configuration options and may change when upgrading to a new Doxygen release.</p>
:::



:::info
<ul class="doxyList ">
<li>If you do not want documentation for each item inside the configuration file then you can use the optional <span class="doxyComputerOutput">-s</span> option. This can use be used in combination with the <span class="doxyComputerOutput">-u</span> option, to add or strip the documentation from an existing configuration file. To get a minimal configuration file use the <span class="doxyComputerOutput">-x</span> or -x_noenv option to show only the differences from the default Doxygen configuration file. Please use the <span class="doxyComputerOutput">-s</span> or <span class="doxyComputerOutput">-x</span> or <span class="doxyComputerOutput">-x_noenv</span> option if you send me a configuration file as part of a bug report or post an issue on GitHub! (see also: <a href="/web-doxygen/docs/pages/trouble/#bug_reports">How to report a bug</a>)</li>
<li>To make Doxygen read/write to standard input/output instead of from/to a file, use <span class="doxyComputerOutput">-</span> for the file name.</li>
</ul>
:::

 
Go to the <a href="/docs/pages/doxywizard-usage/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
