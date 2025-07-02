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




Doxygen provides a large number of <a href="/web-doxygen/docs/pages/commands">special commands</a>, <a href="/web-doxygen/docs/pages/xmlcmds">XML commands</a>, and <a href="/web-doxygen/docs/pages/htmlcmds">HTML commands</a>. that can be used to enhance or structure the documentation inside a comment block. If you for some reason have a need to define new commands you can do so by means of an <em>alias</em> definition.

The definition of an alias should be specified in the configuration file using the <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> configuration tag.

## Simple aliases {#custcmd_simple}


The simplest form of an alias is a simple substitution of the form


<pre><code> name=value
</code></pre>


For example defining the following alias:


<pre><code> ALIASES += sideeffect="\par Side Effects:^^"
</code></pre>


will allow you to put the command <code>\\sideeffect</code> (or <code>@sideeffect</code>) in the documentation, which will result in a user-defined paragraph with heading <b>Side Effects:</b>.

Note that you cannot put <code>\\n</code>'s in the value part of an alias to insert newlines (in the resulting output). You can put <code>^^</code> in the value part of an alias to insert a newline as if a physical newline was in the original file.

Note when you need a literal <code>{</code> or <code>}</code> or <code>,</code> (or non default separator) in the value part of an alias you have to escape it by means of a backslash (<code>\\</code>), this can lead to conflicts with the commands <code>\\{</code> and <code>\\}</code> for these it is advised to use the version <code>@{</code> and <code>@}</code> or use a double escape (<code>\\\\{</code> and <code>\\\\}</code>)

Also note that you can redefine existing special commands if you wish.

Some commands, such as <a href="/web-doxygen/docs/pages/commands/#cmdxrefitem">\\xrefitem</a> are designed to be used in combination with aliases.

## Aliases with arguments {#custcmd_complex}


Aliases can also have one or more arguments. In the alias definition you then need to specify the number of arguments between curly braces. In the value part of the definition you can place <code>\\x</code> markers, where '<code>x</code>' represents the argument number starting with 1.

Here is an example of an alias definition with a single argument:


<pre><code>ALIASES += l{1}="\ref \1"
</code></pre>


Inside a comment block you can use it as follows


<pre><code>/** See \l{SomeClass} for more information. */
</code></pre>


which would be the same as writing


<pre><code>/** See \ref SomeClass for more information. */
</code></pre>


Note that you can overload an alias by a version with multiple arguments, for instance:


<pre><code>ALIASES += l{1}="\ref \1"
ALIASES += l{2}="\ref \1 \"\2\""
</code></pre>


Note that the quotes inside the alias definition have to be escaped with a backslash.

With these alias definitions, we can write


<pre><code>/** See \l{SomeClass,Some Text} for more information. */
</code></pre>


inside the comment block and it will expand to


<pre><code>/** See \ref SomeClass "Some Text" for more information. */
</code></pre>


where the command with a single argument would still work as shown before.

Aliases can also be expressed in terms of other aliases, e.g. a new command <code>\\reminder</code> can be expressed as a <a href="/web-doxygen/docs/pages/commands/#cmdxrefitem">\\xrefitem</a> via an intermediate <code>\\xreflist</code> command as follows:


<pre><code>ALIASES += xreflist{3}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders,Reminder,Reminders}"
</code></pre>


Note that if for aliases with more than one argument a comma is used as a separator, if you want to put a comma inside the command, you will need to escape it with a backslash, i.e.


<pre><code>\l{SomeClass,Some text\, with an escaped comma}
</code></pre>


given the alias definition of <code>\\l</code> in the example above.

By default the separator for arguments in an alias is a comma. However, for arguments with a lot of commas, such as templates of function definitions, escaping each comma can be cumbersome. To solve this, one can specify a different separator, directly after the parameter count, for example to use a semicolon as separator one can define the command as follows:


<pre><code>ALIASES += xreflist{3;}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders;Reminder;Reminders}"
</code></pre>


Note that also multi-character separators are allowed, i.e. the same example can be written using double pipe symbols as separator:


<pre><code>ALIASES += xreflist{3||}="\xrefitem \1 \"\2\" \"\3\" "
ALIASES += reminder="\xreflist{reminders||Reminder||Reminders}"
</code></pre>


The following characters are allowed to create separators:


<pre><code>!#$%&amp;,.?|;:'+=~`/
</code></pre>


Note that for each command and number of parameters, one can use a different separator. It is not recommended to select a different separator for same command however, as this may lead to ambiguity as to which command definition is to be used. Doxygen resolves such ambiguity by choosing the command which matches the most parameters. Consider the following, rather contrived example:


<pre><code>ALIASES += v{2+}="Choose 2: '\1' and '\2'"
ALIASES += v{3;}="Choose 3: '\1', '\2', and '\3'"
</code></pre>


Then


<pre><code>- \v{One+Two}
- \v{One;Two;Three}
- \v{One+Two;Three;Four}
</code></pre>


Will produce:

<ul class="doxyList ">
<li>Choose 2: 'One' and 'Two'</li>
<li>Choose 3: 'One', 'Two', and 'Three'</li>
<li>Choose 3: 'One+Two', 'Three', and 'Four'</li>
</ul>

For the last command both definitions of <code>v</code> match, but the one with 3 parameters is selected as it matches more parameters.

## Nesting custom command {#custcmd_nesting}


You can use commands as arguments of aliases, including commands defined using aliases.

As an example consider the following alias definitions


<pre><code>ALIASES += Bold{1}="&lt;b&gt;\1&lt;/b&gt;"
ALIASES += Emph{1}="&lt;em&gt;\1&lt;/em&gt;"
</code></pre>


Inside a comment block you can now use:


<pre><code>/** This is a \Bold{bold \Emph{and} Emphasized} text fragment. */
</code></pre>


which will expand to


<pre><code>/** This is a &lt;b&gt;bold &lt;em&gt;and&lt;/em&gt; Emphasized&lt;/b&gt; text fragment. */
</code></pre>

 
<br/>
Go to the <a href="/docs/pages/external/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
