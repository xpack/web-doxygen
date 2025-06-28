---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/custcmd
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Custom Commands




<p>Doxygen provides a large number of <a href="/web-doxygen/docs/pages/commands">special commands</a>, <a href="/web-doxygen/docs/pages/xmlcmds">XML commands</a>, and <a href="/web-doxygen/docs/pages/htmlcmds">HTML commands</a>. that can be used to enhance or structure the documentation inside a comment block. If you for some reason have a need to define new commands you can do so by means of an <em>alias</em> definition.</p>

<p>The definition of an alias should be specified in the configuration file using the <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> configuration tag.</p>

## Simple aliases {#custcmd_simple}


<p>The simplest form of an alias is a simple substitution of the form</p>


<pre><code>name=value
</code></pre>


<p>For example defining the following alias:</p>


<pre><code>ALIASES += sideeffect="\par Side Effects:^^"
</code></pre>


<p>will allow you to put the command <span class="doxyComputerOutput">\sideeffect</span> (or <span class="doxyComputerOutput">@sideeffect</span>) in the documentation, which will result in a user-defined paragraph with heading <b>Side Effects:</b>.</p>

<p>Note that you cannot put <span class="doxyComputerOutput">\n</span>'s in the value part of an alias to insert newlines (in the resulting output). You can put <span class="doxyComputerOutput">^^</span> in the value part of an alias to insert a newline as if a physical newline was in the original file.</p>

<p>Note when you need a literal <span class="doxyComputerOutput">{</span> or <span class="doxyComputerOutput">}</span> or <span class="doxyComputerOutput">,</span> (or non default separator) in the value part of an alias you have to escape it by means of a backslash (<span class="doxyComputerOutput">\</span>), this can lead to conflicts with the commands <span class="doxyComputerOutput">\{</span> and <span class="doxyComputerOutput">\}</span> for these it is advised to use the version <span class="doxyComputerOutput">@{</span> and <span class="doxyComputerOutput">@}</span> or use a double escape (<span class="doxyComputerOutput">\\{</span> and <span class="doxyComputerOutput">\\}</span>)</p>

<p>Also note that you can redefine existing special commands if you wish.</p>

<p>Some commands, such as <a href="/web-doxygen/docs/pages/commands/#cmdxrefitem">\xrefitem</a> are designed to be used in combination with aliases.</p>

## Aliases with arguments {#custcmd_complex}


<p>Aliases can also have one or more arguments. In the alias definition you then need to specify the number of arguments between curly braces. In the value part of the definition you can place <span class="doxyComputerOutput">\x</span> markers, where '<span class="doxyComputerOutput">x</span>' represents the argument number starting with 1.</p>

<p>Here is an example of an alias definition with a single argument:</p>


<pre><code>ALIASES += l{1}="\ref \1"
</code></pre>


<p>Inside a comment block you can use it as follows</p>


<pre><code>/** See \l{SomeClass} for more information. */
</code></pre>


<p>which would be the same as writing</p>


<pre><code>/** See \ref SomeClass for more information. */
</code></pre>


<p>Note that you can overload an alias by a version with multiple arguments, for instance:</p>


<pre><code>ALIASES += l{1}="\ref \1"
ALIASES += l{2}="\ref \1 \"\2\""
</code></pre>


<p>Note that the quotes inside the alias definition have to be escaped with a backslash.</p>

<p>With these alias definitions, we can write</p>


<pre><code>/** See \l{SomeClass,Some Text} for more information. */
</code></pre>


<p>inside the comment block and it will expand to</p>


<pre><code>/** See \ref SomeClass "Some Text" for more information. */
</code></pre>


<p>where the command with a single argument would still work as shown before.</p>

<p>Aliases can also be expressed in terms of other aliases, e.g. a new command <span class="doxyComputerOutput">\reminder</span> can be expressed as a <a href="/web-doxygen/docs/pages/commands/#cmdxrefitem">\xrefitem</a> via an intermediate <span class="doxyComputerOutput">\xreflist</span> command as follows:</p>


<pre><code>ALIASES += xreflist{3}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders,Reminder,Reminders}"
</code></pre>


<p>Note that if for aliases with more than one argument a comma is used as a separator, if you want to put a comma inside the command, you will need to escape it with a backslash, i.e.</p>


<pre><code>\l{SomeClass,Some text\, with an escaped comma}
</code></pre>


<p>given the alias definition of <span class="doxyComputerOutput">\l</span> in the example above.</p>

<p>By default the separator for arguments in an alias is a comma. However, for arguments with a lot of commas, such as templates of function definitions, escaping each comma can be cumbersome. To solve this, one can specify a different separator, directly after the parameter count, for example to use a semicolon as separator one can define the command as follows:</p>


<pre><code>ALIASES += xreflist{3;}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders;Reminder;Reminders}"
</code></pre>


<p>Note that also multi-character separators are allowed, i.e. the same example can be written using double pipe symbols as separator:</p>


<pre><code>ALIASES += xreflist{3||}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders||Reminder||Reminders}"
</code></pre>


<p>The following characters are allowed to create separators:</p>


<pre><code>!#$%&amp;,.?|;:'+=~`/
</code></pre>


<p>Note that for each command and number of parameters, one can use a different separator. It is not recommended to select a different separator for same command however, as this may lead to ambiguity as to which command definition is to be used. Doxygen resolves such ambiguity by choosing the command which matches the most parameters. Consider the following, rather contrived example:</p>


<pre><code>ALIASES += v{2+}="Choose 2: '\1' and '\2'"
ALIASES += v{3;}="Choose 3: '\1', '\2', and '\3'"
</code></pre>


<p>Then</p>


<pre><code>- \v{One+Two}
- \v{One;Two;Three}
- \v{One+Two;Three;Four}
</code></pre>


<p>Will produce:</p>

<ul class="doxyList ">
<li>Choose 2: 'One' and 'Two'</li>
<li>Choose 3: 'One', 'Two', and 'Three'</li>
<li>Choose 3: 'One+Two', 'Three', and 'Four'</li>
</ul>

<p>For the last command both definitions of <span class="doxyComputerOutput">v</span> match, but the one with 3 parameters is selected as it matches more parameters.</p>

## Nesting custom command {#custcmd_nesting}


<p>You can use commands as arguments of aliases, including commands defined using aliases.</p>

<p>As an example consider the following alias definitions</p>


<pre><code>ALIASES += Bold{1}="&lt;b&gt;\1&lt;/b&gt;"
ALIASES += Emph{1}="&lt;em&gt;\1&lt;/em&gt;"
</code></pre>


<p>Inside a comment block you can now use:</p>


<pre><code>/** This is a \Bold{bold \Emph{and} Emphasized} text fragment. */
</code></pre>


<p>which will expand to</p>


<pre><code>/** This is a &lt;b&gt;bold &lt;em&gt;and&lt;/em&gt; Emphasized&lt;/b&gt; text fragment. */
</code></pre>

 
<br/>
Go to the <a href="/docs/pages/external/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
