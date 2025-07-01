---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/formulas
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Including formulas




Doxygen allows you to put <code>{\LaTeX}</code> formulas in the output (this works only for the HTML, <code>{\LaTeX}</code> and RTF output. To be able to include formulas (as images) in the HTML and RTF documentation, you will also need to have the following tools installed

<ul class="doxyList ">
<li><span class="doxyComputerOutput">latex:</span> the <code>{\LaTeX}</code> compiler, needed to parse the formulas. To test I have used the teTeX 1.0 distribution.</li>
<li><span class="doxyComputerOutput">dvips:</span> a tool to convert DVI files to PostScript files I have used version 5.92b from Radical Eye software for testing.</li>
<li><span class="doxyComputerOutput">gs:</span> the GhostScript interpreter for converting PostScript files to bitmaps. I have used Aladdin GhostScript 8.0 for testing.</li>
</ul>

For the HTML output there is also an alternative solution using <a href="https://www.mathjax.org">MathJax</a> which does not require the above tools. If you enable <a href="/web-doxygen/docs/pages/config/#cfg_use_mathjax">USE\_MATHJAX</a> in the configuration then the latex formulas will be copied to the HTML "as is" and a client side JavaScript will parse them and turn them into (interactive) images.

There are four ways to include formulas in the documentation.

<ol class="doxyList" type="1">
<li>Using in-text formulas that appear in the running text. These formulas should be put between a pair of <a href="/web-doxygen/docs/pages/commands/#cmdfdollar">\f$</a> commands, so


<pre><code>  The distance between \f$(x_1,y_1)\f$ and \f$(x_2,y_2)\f$ is 
  \f$\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}\f$.
</code></pre>


results in:

The distance between <code>$(x\_1,y\_1)$</code> and <code>$(x\_2,y\_2)$</code> is <code>$\sqrt{(x\_2-x\_1)^2+(y\_2-y\_1)^2}$</code>. 
<br/></li>
<li>Using in-text formulas that appear in the running text, contrary to <a href="/web-doxygen/docs/pages/commands/#cmdfdollar">\f$</a> it will not explicitly open the math mode in <code>{\LaTeX}</code>. These formulas should be put between <a href="/web-doxygen/docs/pages/commands/#cmdfrndclose">\f(</a> and <a href="/web-doxygen/docs/pages/commands/#cmdfrndopen">\f)</a> commands, so


<pre><code>  The LaTeX and Tex logos are: \f(\LaTeX \f) and \f(\TeX \f).
</code></pre>


results in:

The LaTeX and Tex logos are: <code>{\LaTeX}</code> and <code>{\TeX}</code>. 
<br/></li>
<li>Unnumbered displayed formulas that are centered on a separate line. These formulas should be put between <a href="/web-doxygen/docs/pages/commands/#cmdfbropen">\f\[</a> and <a href="/web-doxygen/docs/pages/commands/#cmdfbrclose">\f\]</a> commands. An example:


<pre><code>  \f[
    |I_2|=\left| \int_{0}^T \psi(t) 
             \left\{ 
                u(a,t)-
                \int_{\gamma(t)}^a 
                \frac{d\theta}{k(\theta,t)}
                \int_{a}^\theta c(\xi)u_t(\xi,t)\,d\xi
             \right\} dt
          \right|
  \f]
</code></pre>


results in:          <code>\\[    |I\_2|=\left| \int\_{0}^T \psi(t) 
             \left\{ 
                u(a,t)-
                \int\_{\gamma(t)}^a 
                \frac{d\theta}{k(\theta,t)}
                \int\_{a}^\theta c(\xi)u\_t(\xi,t)\,d\xi
             \right\} dt
          \right|
\\]</code></li>
<li>Formulas or other latex elements that are not in a math environment can be specified using <a href="/web-doxygen/docs/pages/commands/#cmdfcurlyopen">\f{environment}</a>, where <span class="doxyComputerOutput">environment</span> is the name of the <code>{\LaTeX}</code> environment, the corresponding end command is <a href="/web-doxygen/docs/pages/commands/#cmdfcurlyclose">\f}</a>. Here is an example for an equation array


<pre><code>   \f{eqnarray*}{
        g &amp;=&amp; \frac{Gm_2}{r^2} \\ 
          &amp;=&amp; \frac{(6.673 \times 10^{-11}\,\mbox{m}^3\,\mbox{kg}^{-1}\,
              \mbox{s}^{-2})(5.9736 \times 10^{24}\,\mbox{kg})}{(6371.01\,\mbox{km})^2} \\ 
          &amp;=&amp; 9.82066032\,\mbox{m/s}^2
   \f}
</code></pre>


which results in:      <code>\begin{eqnarray\*}        g &amp;=&amp; \frac{Gm\_2}{r^2} \\ 
          &amp;=&amp; \frac{(6.673 \times 10^{-11}\,\mbox{m}^3\,\mbox{kg}^{-1}\,
              \mbox{s}^{-2})(5.9736 \times 10^{24}\,\mbox{kg})}{(6371.01\,\mbox{km})^2} \\ 
          &amp;=&amp; 9.82066032\,\mbox{m/s}^2
\end{eqnarray\*}</code></li>
</ol>

For the first and third commands one should make sure formulas contain valid commands in <code>{\LaTeX}</code>'s math-mode. The second command should valid text-mode commands that also work in math-mode when using <a href="/web-doxygen/docs/pages/config/#cfg_use_mathjax">USE\_MATHJAX</a>. For the fourth command the section should contain valid command for the specific environment.

:::warning
Currently, Doxygen is not very fault tolerant in recovering from typos in formulas. It may be necessary to remove the files <span class="doxyComputerOutput">formula.repository</span> that are written to the html, rtf etc. directories to get rid of an incorrect formula as well as the <span class="doxyComputerOutput">form\_\*</span> files.
:::


To have the possibility to define your own <code>{\LaTeX}</code> commands, for e.g. formula building blocks or consistent writing of certain words, the configuration option <a href="/web-doxygen/docs/pages/config/#cfg_formula_macrofile">FORMULA\_MACROFILE</a> can be used. to supply a file with <code>{\LaTeX}</code> commands. This file can contain <code>{\LaTeX}</code> <span class="doxyComputerOutput">\newcommand</span> and <span class="doxyComputerOutput">\renewcommand</span> commands and they are included formulas (image version and MathJax version) as well as in the generated <code>{\LaTeX}</code> output (for PDF generation).
<br/>
 The <span class="doxyComputerOutput">\newcommand</span> (and <span class="doxyComputerOutput">\renewcommand</span>) are restricted to a version without optional parameters so only the following types are supported:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\cmd}{replacement}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\cmd}[nr]{replacement}</span></span></div>

</div>


e.g.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\E}{\mathrm{E}}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\ccSum}[3]{\sum_{#1}^{#2}{#3}}</span></span></div>

</div>

 
Go to the <a href="/docs/pages/tables/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
