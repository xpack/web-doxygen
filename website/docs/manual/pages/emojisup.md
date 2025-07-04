---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/emojisup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Emoji support




<p>The <a href="http://www.unicode.org/">Unicode consortium</a> has defined a set of <a href="https://en.wikipedia.org/wiki/Emoji">emoji</a> with the corresponding Unicode sequences. Doxygen supports the subset of emoji characters as used by GitHub (based on the list <a href="https://api.github.com/emojis">https://api.github.com/emojis</a>). An emoji is created using the <a href="/web-doxygen/docs/pages/commands/#cmdemoji">\emoji</a> command. For example <span class="doxyComputerOutput">\emoji smile</span> or <span class="doxyComputerOutput">\emoji :smile:</span> both produce <span class="doxyEmoji">&#x1f604;</span>}.</p>


## Representation {#emojirep}


<p>For the different Doxygen output types there is an output defined:</p>


<ul class="doxyList ">
<li>Unicode code sequence, the actual representation is depending on the possibilities of the fonts loaded:

<ul class="doxyList ">
<li>HTML</li>
<li>DocBook</li>
<li>RTF, converted to UTF-16 representation.</li>
</ul></li>
<li>Image

<ul class="doxyList ">
<li><code>{\LaTeX}</code>, in case the image can be found (see <a href="#emojiimage">Emoji image retrieval</a>) otherwise the plain emoji text (i.e. <span class="doxyComputerOutput">:&lt;text&gt;:</span>) is displayed</li>
</ul></li>
<li>plain emoji text (i.e. <span class="doxyComputerOutput">:&lt;text&gt;:</span>)

<ul class="doxyList ">
<li>man</li>
<li>perl</li>
</ul></li>
<li>For XML there is a dedicated <span class="doxyComputerOutput">&lt;emoji&gt;</span> tag with <span class="doxyComputerOutput">name</span> and <span class="doxyComputerOutput">unicode</span> attributes.</li>
</ul>

## Emoji image retrieval {#emojiimage}


<p>In the list of images can be downloaded via the following Python script:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"># script to download the emoticons from GitHub and to produce a table for</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"># inclusion in Doxygen. Works with python 2.7+ and python 3.x</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> json</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> os</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> argparse</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> re</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">try</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> urllib.request </span><span class="doxyHighlightKeyword">as</span><span class="doxyHighlight"> urlrequest</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">except</span><span class="doxyHighlight"> ImportError:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">import</span><span class="doxyHighlight"> urllib </span><span class="doxyHighlightKeyword">as</span><span class="doxyHighlight"> urlrequest</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">unicode_re = re.compile(</span><span class="doxyHighlightStringLiteral">r'.*?/unicode/(.*?).png\?.*'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">get_emojis():</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    response  = urlrequest.urlopen(</span><span class="doxyHighlightStringLiteral">'https://api.github.com/emojis'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    raw_data  = response.read()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> json.loads(raw_data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">download_images(dir_name, silent):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">not</span><span class="doxyHighlight"> os.path.exists(dir_name):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        os.makedirs(dir_name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    json_data = get_emojis()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    num_items = len(json_data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    cur_item=0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> image,url </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight"> sorted(json_data.items()):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        image_name = image+</span><span class="doxyHighlightStringLiteral">'.png'</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        cur_item=cur_item+1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> url.find(</span><span class="doxyHighlightStringLiteral">'/unicode/'</span><span class="doxyHighlight">)==-1 </span><span class="doxyHighlightKeywordFlow">or</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">not</span><span class="doxyHighlight"> os.path.isfile(dir_name+</span><span class="doxyHighlightStringLiteral">'/'</span><span class="doxyHighlight">+image_name):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            success = </span><span class="doxyHighlightKeyword">True</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">with</span><span class="doxyHighlight"> open(dir_name+</span><span class="doxyHighlightStringLiteral">'/'</span><span class="doxyHighlight">+image_name,</span><span class="doxyHighlightStringLiteral">'wb'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeyword">as</span><span class="doxyHighlight"> file:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">not</span><span class="doxyHighlight"> silent:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                    print(</span><span class="doxyHighlightStringLiteral">'%s/%s: fetching %s'</span><span class="doxyHighlight"> % (cur_item,num_items,image_name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">try</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                    file.write(urlrequest.urlopen(url).read())</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">except</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                    print(</span><span class="doxyHighlightStringLiteral">'Unable to fetch %s'</span><span class="doxyHighlight"> % (image_name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                    success = </span><span class="doxyHighlightKeyword">False</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">not</span><span class="doxyHighlight"> success:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                os.remove(dir_name+</span><span class="doxyHighlightStringLiteral">'/'</span><span class="doxyHighlight">+image_name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">not</span><span class="doxyHighlight"> silent:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                print(</span><span class="doxyHighlightStringLiteral">'%s/%s: skipping %s'</span><span class="doxyHighlight"> % (cur_item,num_items,image_name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">def </span><span class="doxyHighlight">produce_table():</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    json_data = get_emojis()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    lines = []</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> image,url </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight"> sorted(json_data.items()):</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        match = unicode_re.match(url)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> match:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            unicodes = match.group(1).split(</span><span class="doxyHighlightStringLiteral">'-'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            unicodes_html = </span><span class="doxyHighlightStringLiteral">''</span><span class="doxyHighlight">.join([</span><span class="doxyHighlightStringLiteral">"&amp;#x"</span><span class="doxyHighlight">+x+</span><span class="doxyHighlightStringLiteral">";"</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> x </span><span class="doxyHighlightKeywordFlow">in</span><span class="doxyHighlight"> unicodes])</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            image_str = </span><span class="doxyHighlightStringLiteral">"\":"</span><span class="doxyHighlight">+image+</span><span class="doxyHighlightStringLiteral">":\","</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            unicode_str = </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">+unicodes_html+</span><span class="doxyHighlightStringLiteral">"\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">            lines.append(</span><span class="doxyHighlightStringLiteral">'  { %-42s %-38s }'</span><span class="doxyHighlight"> % (image_str,unicode_str))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    out_str = </span><span class="doxyHighlightStringLiteral">',\n'</span><span class="doxyHighlight">.join(lines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    print(</span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    print(out_str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    print(</span><span class="doxyHighlightStringLiteral">"};"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> __name__==</span><span class="doxyHighlightStringLiteral">"__main__"</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    parser = argparse.ArgumentParser()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    parser.add_argument(</span><span class="doxyHighlightStringLiteral">'-d'</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">'--dir'</span><span class="doxyHighlight">,help=</span><span class="doxyHighlightStringLiteral">'directory to place images in'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    parser.add_argument(</span><span class="doxyHighlightStringLiteral">'-t'</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">'--table'</span><span class="doxyHighlight">,help=</span><span class="doxyHighlightStringLiteral">'generate code fragment'</span><span class="doxyHighlight">,action=</span><span class="doxyHighlightStringLiteral">'store_true'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    parser.add_argument(</span><span class="doxyHighlightStringLiteral">'-s'</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">'--silent'</span><span class="doxyHighlight">,help=</span><span class="doxyHighlightStringLiteral">'silent mode'</span><span class="doxyHighlight">,action=</span><span class="doxyHighlightStringLiteral">'store_true'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    args = parser.parse_args()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> args.table:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        produce_table()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> args.dir:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        download_images(args.dir, args.silent)</span></span></div>

</div>


<p>When invoking the script with the <span class="doxyComputerOutput">-d image_dir</span> option, the images will by downloaded to the <span class="doxyComputerOutput">image_dir</span> directory.</p>


<p>When invoking the script with the <span class="doxyComputerOutput">-s</span> option, no progress messages are shown while fetching the images, except for when fetching an image fails.</p>


<p>By means of the Doxygen configuration parameter <a href="/web-doxygen/docs/pages/config/#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a> the requested directory can be selected.</p>


<p>For convenience a zip with the result of running the script can also be downloaded from <a href="https://www.doxygen.nl/dl/github_emojis.zip">https://www.doxygen.nl/dl/github_emojis.zip</a></p>


<p>For an overview of the supported emoji one can issue the command:
<br/>
 <span class="doxyComputerOutput">doxygen -f emoji &lt;outputFileName&gt;</span></p>

 
Go to the <a href="/docs/pages/langhowto/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
