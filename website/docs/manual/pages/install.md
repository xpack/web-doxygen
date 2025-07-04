---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/install
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Installation




<p>First go to the <a href="https://www.doxygen.org/download.html">download</a> page to get the latest distribution, if you have not downloaded Doxygen already.</p>


## Compiling from source on UNIX {#install_src_unix}


<p>If you downloaded the source distribution, you need at least the following to build the executable:</p>


<ul class="doxyList ">
<li>The <a href="ftp://prep.ai.mit.edu/pub/gnu/">GNU</a> tools <span class="doxyComputerOutput">flex</span>, <span class="doxyComputerOutput">bison</span>, <span class="doxyComputerOutput">libiconv</span> and <span class="doxyComputerOutput">GNU make</span></li>
<li>You need <span class="doxyComputerOutput">python</span> (version 2.7 or higher, see <a href="https://www.python.org">https://www.python.org</a>).</li>
<li>In order to generate a <span class="doxyComputerOutput">Makefile</span> for your platform, you need <a href="https://cmake.org/">cmake</a> version 3.14 or later.</li>
</ul>

<p>To take full advantage of Doxygen's features the following additional tools should be installed.</p>


<ul class="doxyList ">
<li>Qt Software's GUI toolkit <a href="https://doc.qt.io/">Qt</a>  version 5.14 or higher (including Qt 6). This is needed to build the GUI front-end Doxywizard.</li>
<li>A <code>{\LaTeX}</code> distribution: for instance <a href="https://tug.org/interest.html#free">TeX Live</a> This is needed for generating <code>{\LaTeX}</code>, Postscript, and PDF output.</li>
<li><a href="https://www.graphviz.org/">the Graph visualization toolkit version 2.38 or higher</a> Needed for the include dependency graphs, the graphical inheritance graphs, and the collaboration graphs. If you compile graphviz yourself, make sure you do include freetype support (which requires the freetype library and header files), otherwise the graphs will not render proper text labels.</li>
<li>For formulas in the HTML output (when MathJax is not used) or in case you do not wish to use <span class="doxyComputerOutput">pdflatex</span>, the ghostscript interpreter is needed. You can find it at <a href="https://www.ghostscript.com/">www.ghostscript.com</a>.</li>
</ul>

<p>For testing at least these additional dependencies should be available:</p>


<ul class="doxyList ">
<li>xmllint (libxml2-ultils)</li>
<li>bibtex (texlive-binaries)</li>
</ul>

<p>Compilation is now done by performing the following steps:</p>


<ol class="doxyList" type="1">
<li>Unpack the archive, unless you already have done that:


<pre><code>gunzip doxygen-$VERSION.src.tar.gz    # uncompress the archive
tar xf doxygen-$VERSION.src.tar       # unpack it
</code></pre>

</li>
<li>Create a build directory (for instance inside the source tree)


<pre><code>cd doxygen-$VERSION
mkdir build
cd build
</code></pre>

</li>
<li>Run cmake with the makefile generator


<pre><code>cmake -G "Unix Makefiles" ..
</code></pre>

<span class="doxyComputerOutput">cmake</span> tries to determine the platform you use, and will look for the requires tools. It will report if something is missing.

If you have Qt-5.14 or higher installed and want to build the GUI front-end, you should enable it as follows:


<pre><code>cmake -Dbuild_wizard=YES ..
</code></pre>

For an overview of other configuration options use


<pre><code>cmake -L ..
</code></pre>

</li>
<li>Compile the program by running make:


<pre><code>make
</code></pre>

The program should compile without problems and the binaries (<span class="doxyComputerOutput">doxygen</span> and optionally <span class="doxyComputerOutput">doxywizard</span>) should be available in the bin directory within the build directory.

</li>
<li>Optional: Generate the user manual.


<pre><code>cmake -Dbuild_doc=YES ..
make docs
</code></pre>

To let Doxygen generate the HTML and PDF documentation.

The HTML directory within the build directory will now contain the html documentation (just point a HTML browser to the file <span class="doxyComputerOutput">index.html</span> in the html directory).

</li>
<li>Optional: static linking

If you want to build a statically linked version of Doxygen that embeds libclang you need to first build LLVM and clang from sources using the following options:


<pre><code>cmake -DLIBCLANG_BUILD_STATIC=ON \
      -DBUILD_SHARED_LIBS=OFF \
      -DLLVM_ENABLE_PIC=OFF \
      -DLLVM_BUILD_LLVM_DYLIB=OFF \
      -DLLVM_BUILD_LLVM_C_DYLIB=OFF \
      -DLLVM_ENABLE_TERMINFO=OFF \
      path_to_llvm_root_source_dir
</code></pre>

and then build Doxygen with these options:


<pre><code>cmake -DCMAKE_BUILD_TYPE=Release \
      "-DCMAKE_FIND_LIBRARY_SUFFIXES=.a" \
      "-ldl;-lz;-lpthread" \
      -Duse_libclang=YES \
      path_to_doxygen_root_source_dir
</code></pre>

</li>
</ol>

## Installing the binaries on UNIX {#install_bin_unix}


<p>After the compilation of the source code do a <span class="doxyComputerOutput">make install</span> to install Doxygen. If you downloaded the binary distribution for Linux, type:</p>



<pre><code>make install
</code></pre>


<p>Binaries are installed into the directory <span class="doxyComputerOutput">/usr/local/bin</span>, man pages in <span class="doxyComputerOutput">/usr/local/man/man1</span> and documentation in <span class="doxyComputerOutput">/usr/local/doc/doxygen</span> To change this just edit the Makefile.</p>



:::info
<p>You need the GNU install tool for this to work (it is part of the coreutils package). Other install tools may put the binaries in the wrong directory!</p>
:::


<p>If you have a RPM or DEB package, then please follow the standard installation procedure that is required for these packages.</p>


## Compiling from source on Windows {#install_src_windows}


<p>From version 1.8.10 onwards, build files need to be generated by cmake. cmake can be downloaded from <a href="https://cmake.org/download/">https://cmake.org/download/</a></p>


<p>At the moment only the community version of Visual Studio 2019 is tested, but other version might also work.</p>


<p>Alternatively, you can compile Doxygen <a href="#install_src_unix">the UNIX way</a> using <a href="https://en.wikipedia.org/wiki/Cygwin">Cygwin</a> or <a href="https://www.mingw-w64.org/">MinGW</a>.</p>


<p>The next step is to install modern versions of <span class="doxyComputerOutput">bison</span> and <span class="doxyComputerOutput">flex</span> (see <a href="https://sourceforge.net/projects/winflexbison/">https://sourceforge.net/projects/winflexbison/</a>. After installation and adding them to your <span class="doxyComputerOutput">path</span> rename <span class="doxyComputerOutput">win_flex.exe</span> to <span class="doxyComputerOutput">flex.exe</span> and <span class="doxyComputerOutput">win_bison.exe</span> to <span class="doxyComputerOutput">bison.exe</span>)  Furthermore you have to install <span class="doxyComputerOutput">python</span> (version 2.7 or higher, see <a href="https://www.python.org">https://www.python.org</a>). These packages are needed during the compilation process.</p>


<p>Download Doxygen's source tarball and put it somewhere (e.g. use <span class="doxyComputerOutput">c:\tools</span>)</p>


<p>Now start a visual studio native command shell (for either x86 or x64) and type</p>



<pre><code>cd c:\tools
tar zxvf doxygen-x.y.z.src.tar.gz
</code></pre>


<p>to unpack the sources (you can obtain <span class="doxyComputerOutput">tar</span> from e.g. <a href="https://gnuwin32.sourceforge.net/packages.html">https://gnuwin32.sourceforge.net/packages.html</a>). Alternatively you can use an unpack program, like 7-Zip (see <a href="https://www.7-zip.org/">https://www.7-zip.org/</a>) or use the built-in unpack feature of modern Windows systems).</p>


<p>Now your environment is setup to generate the required project files for Doxygen.</p>


<p>change directory to the <span class="doxyComputerOutput">doxygen-x.y.z</span> directory, create and change to a build directory</p>



<pre><code>mkdir build
cd build
cmake -G "Visual Studio 14 2015" ..
</code></pre>


<p>This will create a project file then can be opened in Visual Studio.</p>


<p>If you prefer compiling from the command prompt you can use the following instead:</p>



<pre><code>mkdir build
cd build
cmake -G "NMake Makefiles" ..
nmake
</code></pre>


<p>Note that compiling Doxywizard requires Qt 5.14 or newer (see <a href="https://doc.qt.io/">https://doc.qt.io/</a>).</p>


<p>Also read the next section for additional tools you may need to install to run Doxygen with certain features enabled.</p>


## Installing the binaries on Windows {#install_bin_windows}


<p>Doxygen comes as a self-installing archive, so installation is extremely simple. Just follow the dialogs.</p>


<p>After installation it is recommended to also download and install GraphViz (version 2.38 or better is highly recommended). Doxygen can use the <span class="doxyComputerOutput">dot</span> tool of the GraphViz package to render nicer diagrams, see the <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> option in the configuration file.</p>


<p>If you want to produce compressed HTML files (see <a href="/web-doxygen/docs/pages/config/#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a>) in the configuration file, then you need the Microsoft HTML help workshop. In the beginning of 2021 Microsoft took the original page, with a.o. the download links, offline the HTML help workshop was already many years in maintenance mode). You can download the HTML help workshop from the web archives at <a href="http://web.archive.org/web/20160201063255/http://download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/htmlhelp.exe">Installation executable</a>.</p>


<p>If you want to produce Qt Compressed Help files (see <a href="/web-doxygen/docs/pages/config/#cfg_qhg_location">QHG_LOCATION</a>) in the configuration file, then you need qhelpgenerator which is part of Qt. You can download Qt from <a href="https://www.qt.io/download">Qt Software Downloads</a>.</p>


<p>In order to generate PDF output or use scientific formulas you will also need to install <a href="https://en.wikipedia.org/wiki/LaTeX">LaTeX</a> and <a href="https://en.wikipedia.org/wiki/Ghostscript">Ghostscript</a>.</p>


<p>For <code>{\LaTeX}</code> a number of distributions exists. Popular ones that should work with Doxygen are <a href="https://miktex.org/">MikTex</a> and <a href="https://www.tug.org/protext/">proTeXt</a>.</p>


<p>Ghostscript can be <a href="https://sourceforge.net/projects/ghostscript/">downloaded</a> from Sourceforge.</p>


<p>After installing <code>{\LaTeX}</code> and Ghostscript you'll need to make sure the tools latex.exe, pdflatex.exe, and gswin32c.exe (or gswin64c.exe) are present in the search path of a command box. Follow <a href="https://www.computerhope.com/issues/ch000549.htm">these</a> instructions if you are unsure and run the commands from a command box to verify it works.</p>

 
Go to the <a href="/docs/pages/starting/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
